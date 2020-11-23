#PRACTICA DE LDAP

Los puntos de rubrica que hay que valorar son el 2.4, 3.3 y el 4.3

##2.4 Comprobamos el acceso al contenido del LDAP 

ldapsearch -b "dc=ldapXX,dc=curso2021" -x | grep dn, muestra el contenido de nuestra base de datos LDAP. "dn" significa nombre distiguido,
es un identificador que tiene cada nodo dentro del árbol LDAP.


ldapsearch -H ldap://localhost -b "dc=ldapXX,dc=curso2021" -W -D "cn=Directory Manager" | grep dn, en este caso hacemos la consulta usando usuario/clave.

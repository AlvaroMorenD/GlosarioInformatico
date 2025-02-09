# Servicios de Directorios

Un Servicio de Directorio es un sistema que almacena, organiza y gestiona información sobre usuarios, dispositivos y recursos dentro de una red. Se utilizan principalmente en entornos empresariales para facilitar la autenticación de usuarios, la administración de permisos y la gestión centralizada de recursos.

## Características principales de un Servicio de Directorio

- Se encarga de Almacenar información estructurada → Usuarios, grupos, computadoras, impresoras, etc.
- Autenticación centralizada → Los usuarios pueden acceder a los recursos con una única cuenta.
- Control de acceso → Define qué usuarios pueden acceder a qué recursos.
- Escalabilidad → Permite administrar miles o millones de registros.
- Protocolos estándar → Utiliza **LDAP** (Lightweight Directory Access Protocol) para consultas y modificaciones.

  #### Unos de los SW más reconocidos de servicios de directorios son Active Directory de windows y OpenLDAP por Ubuntu

## Active Directory 

Como hemos dicho antes, fue desarrollado por Windows para el control básico de una red. Se forma por un administrador que adminsitra quien debe de tener x permisos, a donde puede tener acceso y a donde no, etc.... Vamos a ver los tipos de objetos que se encuentran en active directory:

- Los Usuarios → usuarios con distintos niveles de permisos 
- Los Grupos → grupos formados por usuarios 
- El Dominio → Es una agrupación de usuarios, computadoras y recursos dentro de la red.
- Los Árboles → Conjunto de dominios relacionados bajo un mismo nombre raíz.
- Los Bosque → Conjunto de varios árboles de dominios diferentes.

## OpenLDAP

Es un SW de código abierto que su estructura está definida como un árbol. Es más dificil de utilizar ya que carece de interfaz gráfica. Se forma por:

- Dominio Raiz → Al igual que Active Directory
- Usaurio y grupos
- Unidad organizativa → donde se estrucuturan los diferentes objetos
- Servicios → servicios que se van a emplear

En conclusión. OPENLDAP es más dificil de utilizar que ACtive Directory. OPENLADAP se forma por protocolos más funcionales que el de Windows y además tiene mucha más compatibilidad, Active Directory es solo para Windows

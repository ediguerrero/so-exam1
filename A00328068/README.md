# Parcial 1

### **Nombre:** edisson guerrero
### **Código:** A00328068
### **Curso:** Sistemas Operativos
### **Correo:** edixon_guerrero96@hotmail.com

# Descripción
aquí se encuentra el desarrollo del parcial 1 del curso sistemas operativos, en donde realiza la instalación y el uso de la máquina virtual debian 9
# punto 3
### validación
1. descargar la iso de debian 
2. buscar el checksum que pertenece a la iso en el enlace http://cdimage.debian.org/debian-cd/current/amd64/iso-cd/MD5SUMS
3. descargar MD5 para verificar el archivo
4. seleccionar la iso y copiar el checksum para ver la compatibilidad con el calculado por el MD5.

![][1]

# punto 5

1. descargar putty de 64 bits

![][15]

2. utilizar el comando ip a para saber el nombre de host

![][16]

3. correr putty,colocar la ip obtenida,el protocolo y el puerto

![][17]

4. loguearse con el nombre de usuario escogido en debian y el password, luego loguearse como root y alli la conexion ya esta completa

![][18]

# punto 8
# Centos vs Debian
## tabla de uso de las diferentes distribuciones de linux

![][2]

## tabla comparativa
![][3]

1. si tenemos un servidor nuevo sea la marca que sea es muy probable que con debian requiere la compilación de forma externa de los controladores, haciendo tediosa la instalación, mientras que con centos se pueden instalar sin ningún problema en los servidores físicos.
2. debian tiene soporte para gran cantidad de plataformas o arquitecturas.
3. las personas usan mas debian como se ve en la tabla de uso, esto debido a las diferentes plataformas en las que corre.
4. ambas distribuciones tienen interfaz gráfica
5. centos esta enfocado mas a la seguridad informática que debian, centos ya vienen con un paquete instalado llamado sec linux, en debian hay que instalarlo.
6. debian es mas usado para máquinas virtuales y centos para servidores físicos.
7. el apt-get esta mucho mas optimizado que el yum
8. debian tiene menor uso de disco duro que centos ya que no instala paquetes sin uso.
9. para actualizaciones grandes debian funciona perfectamente en cambio en centos hay que instalar desde cero.
10. si desea aplicaciones con propiedad, como Google Chrome, Steam o Discord, todas tienen paquetes para Debian, mientras que no son compatibles con CentOS, y sería difícil hacer que funcionen.

# punto 4
# instalación
1. crear una nueva partición en virtualbox, con sus respectivos parámetros , tamaño de disco nombre etc
2. iniciar la máquina y escoger la ruta para el arranque del sistema.
3. instalar debian en la opción  graphical install
4. escoger idioma y continuar
5. nombre de la máquina y continuar
6. nombre de dominio (root) y continuar
7. contraseña de superusuario y continuar 
8. nombre para el nuevo usuario(edisson) y continuar
9. nombre para la cuenta (edisson)y continuar
10. clave para el usuario  y continuar
11. hacer el particionado en este caso automatico y continuar
12. desea inicializar con otro cd? no
13. gestor de paquetes colombia-debian.uniminuto.edu
14. esperar instalación
15. luego de 1 hora y media la máquina ha sido instalada
### Información del sistema operativo


```
root@debian:/home/edisson# uname
Linux
```
```
root@debian:/home/edisson# uname -a
Linux debian 4.9.0-6-amd64 #1 SMP Debian 4.9.82-1+deb9u3 (2018-03-02) x86_64 GNU/Linux
```
```
root@debian:/home/edisson# uname -o
GNU/Linux
```
```
root@debian:/home/edisson# uname-m
x86_64
```
![][14]

# punto 7
# importar y exportar máquina virtual
## exportar
1. ir a la opción archivo y seleccionar exportar servicio virtualizado
2. cambiar el formato a ovf para que al importar la máquina no nos salga error o buscar la ruta en la que se guardará y cambiamos el formato a ovf
3. damos exportar
4. allí se demora según sea el peso de la máquina
5. una vez terminado los archivos que quedan son uno .ovf y otro vmdk

![][4]
![][5]
![][6]
![][7]
![][8]

## importar
1. vamos a la opción a archivo y damos en importar servicio virtualizado
2. buscamos la ruta y escogemos el archivo ovf
3. damos importar, esta es mas rapida

![][9]
![][10]
![][11]
![][12]
![][13]




[1]:images/checksum.PNG
[2]:images/comparativa.PNG
[3]:images/usos.PNG
[4]:images/1.PNG
[5]:images/2.PNG
[6]:images/3.PNG
[7]:images/4.PNG
[8]:images/5.PNG
[9]:images/i1.PNG
[10]:images/i2.PNG
[11]:images/i3.PNG
[12]:images/i4.PNG
[13]:images/i5.PNG
[14]:images/carac.PNG
[15]:images/e1.PNG
[16]:images/e2.PNG
[17]:images/e3.PNG
[18]:images/e4.PNG

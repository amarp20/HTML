# **COMANDOS BÁSICOS**

<mark>==stdout: secuencia de salida.==</mark>

<div>stdout: secuencia de salida.</div>

<div>stdout: secuencia de salida.</div>

<div>stdout: secuencia de salida.</div>

<pre><code>stdin: secuencia de entrada.

cat: Muestra el contenido de un archivo ejemplo cat archivo.txt
echo: imprimir texto por pantalla ejemplo echo “Opa Racing”
tee: guarda la salida de un archivo y la muestra ej ls | tee lista.txt
more: muestra el contenido de un archivo grande por páginas.
less: muestra el texto y deja moverse arriba y abajo por él.
ls: Lista el contenido del directorio
cd: Cambia al directorio especificado
cd ~: Vuelve a home
pwd: Muestra el directorio de trabajo actual
mkdir: Crea un nuevo directorio
rm: Elimina un archivo o directorio Para directorio lleno: rm -rf directorio
			        Para directorio vacío: rm -r directorio
           
rmdir: Elimina carpetas vacías. Para eliminar una con contenido: rm –r UNIX

cp: Copia un archivo o directorio 	Archivo: cp registros.txt copiaregistros.txt
				En otro directorio: cp registros.txt /home/Escritorio/ 
De manera recursiva Directorio cp -r /home/alejandro/Escritorio/EXAMEN/ /home/alejandro/Escritorio/EXAMEN3/  
			Copia el directorio actual en un archivo: ls | tee ejemplo2.txt  
		Hace 2 copias del archivo: cat ejemplo2.txt | tee copia1.txt | tee copia2.txt    
mv: Mueve o renombra un archivo o directorio	
          Al directorio superior: mv resumen.txt ../
					A otro directorio: mv registros.txt /home/Escritorio/
          Archivos de un tipo a otro directorio: mv /home/alejandro/Escritorio/proyecto_investigacion/*.txt /home/alejandro/Escritorio/mover/   Si el directorio nuevo no existe hay que crearlo previamente
          Archivos de un nombre a otro directorio: mv /home/alejandro/Escritorio/proyecto_investigacion/copia* /home/alejandro/Escritorio/mover/   Si el directorio nuevo no existe hay que crearlo previamente.
          > Al mover o copiar, si estoy en el directorio en el que se encuentra el archivo vale poner solo el comando, el archivo y el destino, 
          pero si estoy en otro directorio hay que poner comando, archivo, ruta donde está el archivo y ruta donde quiero copiarlo o moverlo. Las barras al principio y fin de las rutas son imprescindibles.

ps: Muestra los procesos en ejecución ejemplo ps aux
kill: Termina un proceso por su ID
top: Muestra los procesos en ejecución en tiempo real
jobs: muestra procesos en segundo plano
bg: envía proceso suspendido a 2º plano ejemplo: bg%1
fg: trae un proceso a primer plano
nano: Abre el editor de texto nano
vi: editor de texto avanzado
touch: crea un archivo vacío o modifica su fecha de modificación

grep: busca en archivos: grep “error” archivo.txt
          Sin distinguir mayúsculas: grep -i "linux" archivo.txt
		      Errores en el ordenador: grep "error" /var/log/syslog

Find: busca archivos en el sistema
chmod: Cambia los permisos de un archivo o directorio
chown: cambia el propietario de un archivo
su: cambia de usuario ejemplo su root, a veces hay que poner sudo su
sudo: ejecuta algo con permisos de admin
locate: busca archivos rápidamente
useradd: crea un usuario
groupadd: crea un grupo
passwd: cambia la contraseña de un usuario
/etc/ passwd: información de usuarios del sistema
/etc/ shadow: información de contraseñas cifradas
Iptables: configura reglas de firewall
Ssh: Conecta a un host remoto usando SSH
la: Ver archivos ocultos

sort: ordena las líneas de dentro del archivo	por orden alfabético: sort -d registros.txt
					Por orden numérico:	sort -n edades.txt
					Por orden inverso: sort -r nombres.txt
					Eliminar duplicados: sort -u nombres.txt
				  Ordenar por el segundo valor y número: sort -k2 -n nombresyedades.txt </pre></code>


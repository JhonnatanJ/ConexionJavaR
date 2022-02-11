# ConexionJavaR

<p>INFORMACIÓN ANTES DE EJECUTAR LA APLICACIÓN</p>
<p>INSTALAR R</p>
	<ul>
		<li>1. Instalar R</li>
		<li>2. Instalar R-Tools</li>
		<li>3. Instalar RStudio(Opcional)</li>
		<li><p>4. Instalar en R las librerias: RServe,reader,NbCluster,EMcluster</p>
	</ul>
	<p>Comando para la instalación de libreria en R:<br> install.packages("<b>Nombre de la libreria")</b><br>Ejemplo: install.packages("RServe")<br></p>
	<ul>
		<li>5. Levantar el servidor en R</li>
	</ul>
	<p>Comandos para levantar un servidor en R utilizando la librería RStudio(la libreria debe estar instalada):<br>
	library("Rserve")<br>
	Rserve(args="--no-save")</p>
	<p>En caso de querer ver si se está ejecutando un servidor en R, se ejecuta el comando:<br>
	system('tasklist /FI "IMAGENAME eq Rserve.exe"')</p>


<p>EN JAVA</p>
	<ul>
		<li>Librerias</li>
	</ul>
	<p>Se necesitan tener agregadas las librerias:</p>
	<p>REngine<br>RServeEngine<br>RServe</p>
	<p><b>OJO:<b> Todas las librerias utilizadas se encuentran en este repositorio, en la carpeta "librerias".</p>
	<p><b>El proyecto fue desarrollado en el IDE Apache Netbeans 12.0 utilizando Java JDK 9 </b></p>


<p> Fecha de creación: 10/02/2022 <p>



	

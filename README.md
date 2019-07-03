# sitioweb
  Este es un sitio web de prueba para Kubernetes más Rancher para implementar un Pipeline básico  
  
 # CREACION DE PAGINA WEB CON RANCHER EN DIGITAL OCEAN
	Crear un proyecto en digital ocean 
	1. Crear proyect
	2. colocarle un nombre
	3. crear proyecto
	
 # Crear un droplet en digital ocean
	1. Crear droplet
	2. Seleccionar la imagen del droplet a crear en este caso rancher
	3. Colocarle un nombre
	4. escoger tipo de seguridad SSH KEY o escoger una si ya se tiene
	5. Crear 
	6. Al crear el droplet copiar la ip que genero
	7. Ir a la terminal de la coputadora local
	8. y entrar a la terminal con el siguiente comando:
			
$ ssh rancher@ip
	
	9. ya adentro del droplet colocar el siguiente comando:
			
$ docker run -d --restart=always -p 8080:8080 rancher/server
		
	10.Ingrear a un navegador y colocar:
		
		https://ip:8080
	11. Esto nos va a dirigir al login y agregamos un  password y confirmamos
	12. Ingresamos a rancher 
# Creacion de Cluster
Esto se hace adentro de rancher logueados en el usuario
	1. ir a la pesta;a de agregar cluster
	2. Ingresar un nombre 
	3. Ahora debemos de crear un pipeline
	4.en la pesta;a PIPELINE le damos configurar
	5.alli elegir github
	6.y saldra un link que dice # click here
	7. Esto nos va  redireccionar a github donde tenemos que crear una app
	8. Hay unos links en el pipeline que son la url a pegar en github
	9. Al darle crear app ya con las url
	10. Nos manda a los repositorios donde debemos de darle # Enable al repositorio de la pagina


  

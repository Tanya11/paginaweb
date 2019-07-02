# sitioweb
  Este es un sitio web de prueba para Kubernetes más Rancher para implementar un Pipeline básico
  
  Se debe de crear una  imagen en digitalocean  y crear el cluster despues  de crearlo agrargar un namespace y loguearse con     google hub

para crear un cluster en digitalocean seguir los siguientes pasos
  1.Cree un clúster y una "prueba" de espacio de nombres en el cluster
  
  2.Cree un registro de muelle "myregistry" en el espacio de nombres "prueba"
  
  3.Implemente una carga de trabajo en el espacio de nombres "predeterminado" especificando una imagen de "myregistry"
Creación de droplet 

Aunque Rancher server puede correr en casi todos los sistemas operativos linux, Rancher Labs también nos ofrece una distribución ligera y optimizada para el uso de contenedores. Esta distribución está disponible en Digital ocean y se llama RancherOS.

Para el tamaño del droplet, voy a escoger el de 2 GB de Ram. Esto lo decidí arbitrariamente mas que todo por costo, pero si vas a manejar muchos contenedores y hosts, lo mejor es tener al menos 4GB de RAM. 

Y por último voy a agregar un ssh key que ya tengo en mi cuenta de DO y que me permitirá conectarme a ese servidor. Si no tienes un SSH key guardado puedes generar uno.

Una vez el droplet es creado y tiene asignada una IP podemos ingresar a el por medio del comando

ssh rancher@ip-address

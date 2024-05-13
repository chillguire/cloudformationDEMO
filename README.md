* region, cuenta IAM, secretos de la infraestructura
* secretos de la aplicacion per se
* flujos
	* se actualiza codigo/app, infra sin cambios
		* se desplega
		* se instala todo igual?
	* se actualiza infraestructura, app sin cambios
		* se desplega
		* user info instala node, npm y mongo en el ec2?
			* *y aparte clona/pull de la app en el mismo repo?*
	* cambios en infraestuctura, cambios en codigo/app
	* se actualiza cdigo/app, infra no existe o esta apagada
	* infra se crea/actualiza, userdata falla (clonacion de app, etc)

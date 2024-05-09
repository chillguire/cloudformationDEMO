* region, cuenta IAM, secretos de la infraestructura
* secretos de la aplicacion per se
* flujo
	* se desplega/actualiza infraestructura
	* user info instala node, npm y mongo en el ec2?
		* *y aparte clona/pull de la app en el mismo repo?*
	* **casos borde/casos a probar**
		* cuando se actualiza la app, infra sin cambios
		* se actualiza la app. infra no existe o esta apagada
		* infra se crea/actualiza, clonacion/pull de app falla
		* **flujo actualizar**
		* **flujo crear**
		* **flujo eliminar**
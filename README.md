* cuenta IAM (Permisos, politica) - secretos de la infraestructura
	* security groups
* secretos de la aplicacion per se

---
* para aws cli estoy usando las mismas credenciales que la infraestructura/github, pero no deberia ser asi
---
* si pausas la instancia y haces deploy de infraestructura, falla
	* pero este comportamiento esta bien?
	* basicamente hay que ver el comportamiento cuando se hace push y eso, pero pausar o iniciar la instancia es cosa del lambda y cloudwatch

* lambda si la instancia ya esta corriendo
* si la instancia no existe
---
* evitar ataques con WAF?
	* apagar cosas si salen del free tier con cloudwatch o asi?
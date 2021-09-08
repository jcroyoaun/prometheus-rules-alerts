# prometheus-rules-alerts

## Caso de uso - creando un rules directory

* Para este modulo, vamos a crear un directorio de "rules" dentro de nuestro directorio raiz de prometheus.

`mkdir rules`

* Copiamos el archivo myrules.yml de este proyecto dentro de rules

* Modificamos el archivo prometheus.yml para agregar lo siguiente en la seccion de rule_files que comienza en la linea 15 : 

```
rule_files:
  - "rules/myrules.yml"
```

* Para crear los record rules, nos vamos al archivo rules/myrules.yml



# Instalando Alertmanager
* https://prometheus.io/download/#alertmanager
* tar -xzf ...
* en prometheus.yml linea 12: 

`localhost:9093'

* Modificamos alertmanager.yml (copiamos el que tenemos en este proyecto)

* iniciamos alertmanager

# Para generar un password para gmail...
* Creamos GMAIL app password
* * Entramos a nuestra cuenta de gmail
* * presionamos el boton de "cuenta" > seguridad > Verificacion en dos pasos
* * Despues de agregar verificacion en dos pasos, volvemos a cuenta > seguridad > presionamos > contrasenas de aplicaciones > aplicacion custom > la nombramos prometheus y copiamos el 16 digit passcode


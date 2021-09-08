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


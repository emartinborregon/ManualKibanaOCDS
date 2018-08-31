# Las herramientas Elastic

## Introducción

Es un conjunto de herramientas que al combinarse crean una plataforma robusta de administración de datos permitiendo la monitorización, consolidación y análisis de los mismos.

Las herramientas que componen este sistema son: ElasticSearch, Logstash y Kibana. Y por las iniciales de estos, el conjunto también es conocido como "stack ELK" o simplemente "ELK".

Estas herramientas son creadas, mantenidas y distribuidas por la compañia [Elastic](elastic.co) desde 2012 y han evolucionado segun las necesidades del mercado. La primera de las herramientas en ser creada fue ElasticSearch en 2004 bajo el nombre de Compass, pero la primera version oficial surge en 2010.

Elastic ofrece sus productos en dos modalidades:
- Como software de codigo abierto, bajo la licensia Apache 2, salvo algunas funcionalidades adicionales son distribuidos con licensia propietaria. Ofrece la oportunidad de ver, utilizar y hasta modificar las herramientas sin costo alguno, pero toda administración de las herramientas debe ser llevado a cabo personalmente.
- Como servicio de pago, Elastic Cloud pone a disposicion todas las herramientas y las funcionalidades adiciones en servidores administrados por ellos.

## Las ventajas de la plataforma ELK

Hay muchas soluciones distintas para cubrir la necesidad de procesamiento, monitoreo y visualizacion de datos, tanto de pago como libres, pero lo que distingue a ELK sobre otras es principalmente:

- Potencia
    Ofrece mucha funcionalidad con un bajo costo técnico, las configuraciones son mínimas para empezar. Y las optimizaciones disponibles son amplias.
- Escalabilidad
    Elasticsearch es una herramienta diseñada para manejar terabytes de datos sin ningún problema. Su arquitectura le permite expandirse de forma rápida y fácil.
- Flexibilidad
    La configuración es flexible y puede adaptarse a cualquier necesidad y entorno.
- Apertura
    Elastic fomenta un ecosistema de extensiones (plugins) alrededor de sus herramientas que han creado un número importante de funcionalidades extras y gratuitas para facilitar el trabajo con ellas.
- Codigo Abierto
    Hoy en dia el código abierto ofrece ventajas competitivas sobre otras plataformas porque permite la rápida correción de errores gracias a la comunidad, la creación de extensiones e incluso incremente la base de usuarios al permitir utilizar las herramientas sin requerir pago alguno, lo que incrementa el conocimiento compartido de las herramientas.

## Los componentes

ELK está compuesta por tres pilares fundamentales: Elasticsearch, Logstash y Kibana.

![Plataforma ELK](elk.png "Plataforma ELK")

Cada componente tiene una funcionalidad y arquitectura específica, veamos uno a uno en la [Sección 2](Seccion2.md)

[Inicio](../README.md) | [Siguiente: Arquitectura de las herramientas Elastic](Seccion2.md)
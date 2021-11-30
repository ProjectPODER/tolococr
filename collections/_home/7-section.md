---
title: Metodología
cta-button-section: false
button:
  link: "https://projectpoder.github.io/tolococr/"
  text: "Botón"
# Media section
media: false
media-type:
  image:
  iframe:
  video:
# Column options
one-column-section: true

# Section background and text colors
background-color: "#ffffff"
text-color: "#333333"

---

{:.text-center}
## METODOLOGÍA

{:.main-letter}
E

l sistema de evaluación Groucho ha sido desarrollado por PODER y funciona a partir de cualquier conjunto de datos que cumpla con el Estándar de Datos de Contrataciones Abiertas (OCDS, por sus siglas en inglés). Para su construcción se revisaron múltiples sistemas de evaluación a nivel mundial como [RED FLAGS for integrity](https://www.open-contracting.org/wp-content/uploads/2016/11/OCP2016-Red-flags-for-integrityshared-1.pdf)  de la Open Contracting Partnership, el [Laboratorio de innovación en la contratación pública](https://civio.es/laboratorio-de-innovacion-en-la-contratacion-publica/), espacio de MediaLab-Prado, el sistema de Banderas de [La Letra Menuda](http://especiales.datasketch.co/contratos-colombia/), realizado por Datasketch o el de [Mihály Fazekas](http://mihalyfazekas.eu) y su equipo. Dentro de todos estos sistemas, Groucho aporta dos novedades: 


+ Adaptación al contexto costarricense: El SICOP publica alrededor de 20 campos de datos por contrato. A éstos les falta información fundamental ubicada en otros sistemas de evaluación como el nombre de todos los ofertantes del contrato, el costo por ítem o información del contrato. Es por ello que solo se aplicaron las normas que se podían medir con el contenido de los datos vigentes. 

+ La red forma parte de la evaluación: Partimos del supuesto de que una organización que realiza una mala práctica en un contrato es probable que intente volver a realizarla en otro contrato. Es por eso que uno de los factores que influencian la puntuación de una organización dada es el promedio de las evaluaciones de contratos de las organizaciones con las que tiene contratos. 

## El proceso de evaluación consta de 4 subprocesos:

1. Evaluación de las banderas de contrato sobre todos los contratos que tenemos
2. Evaluación de las banderas de nodo sobre todas las dependencias 
3. Creación de las medias para cada uno de los contratos y dependencias
4. Bandera de confiabilidad

Las pruebas que se corren están agrupadas en cinco categorías que describen el contrato ideal, entre ellas (i) cuenta con toda la información para entenderlo, (ii) todos los procesos se realizaron en tiempo, (iii) hubo una competencia abierta para ganarlo, (iv) el camino del dinero es trazable, y (v) todos los actores que participan en el proceso son confiables.


A partir de ello se generaron 32 banderas con la siguiente desagregación:


# Transparencia (4 banderas)


+ **OCDS válido**: Los datos cumplen con el Estándar de Datos de Contrataciones Abiertas según la [Herramienta de revisión de datos](https://standard.open-contracting.org/review/) de la OCP. Bandera booleana (si/no).

+ **Campos OCDS completos**: La OCP define que un proceso de contratación tiene 325 campos, en esta bandera medimos cuántos de ellos tiene completos. Bandera en porcentaje.

+ **Secciones completas**: La OCP explica el proceso de contratación en cinco pasos: planificación, licitación, convocatoria, contratación e implementación. La bandera mide que al menos haya un dato para cada uno de los pasos del proceso. Bandera en porcentaje. 


# Temporalidad (6 banderas)


+ **Campos fundamentales**: Existe una fecha válida en los campos publicación de la oportunidad, adjudicación de contrato, inicio de contrato y fin de contrato. Bandera en porcentaje.

+ **Duración del contrato excesivamente larga**: La diferencia entre el inicio y el fin del contrato supera los 1000 días. Bandera booleana (si/no).

+ **Fechas sospechosas**: El contrato se celebra o firma en fechas no laborables del gobierno o feriados oficiales. Bandera booleana (si/no).


# Competitividad (3 banderas)


+ **Campos fundamentales**: Existe un proveedor con nombre válido y se especifica el tipo de procedimiento del contrato. Bandera en porcentaje.

+ **Empresas con domicilios en paraísos fiscales**: El contrato se realiza con una empresa de un país que se considera un paraíso fiscal. Se considera un paraíso fiscal si la puntuación en el [Secrecy Score del Financial Secrecy Index](https://fsi.taxjustice.net/en/introduction/fsi-2018-results) es superior a 66, promedio mundial. Bandera booleana (si/no).

+ **Estimación fuera de rango**: El monto estimado para este contrato está alejado del monto del contrato, lo que podría haber permitido un proceso menos competitivo del apropiado. 



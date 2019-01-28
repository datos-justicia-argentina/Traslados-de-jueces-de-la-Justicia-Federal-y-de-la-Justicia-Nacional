Traslados de jueces de la Justicia Federal y de la Justicia Nacional
====================================================================

En este conjunto de datos se detallan los traslados de jueces de la Justicia Federal y de la Justicia Nacional de la República Argentina. La Oficina Decretos, dependiente de la Subsecretaría de Relaciones con el Poder Judicial y Asuntos Penitenciarios interviene en el trámite de traslado de jueces conforme a lo previsto en la Constitución Nacional y reglamentación complementaria.

http://datos.jus.gob.ar/dataset/traslados-de-jueces-de-la-justicia-federal-y-de-la-justicia-nacional 


Características
---------------

-   **Fecha de Primera Publicación:** 28/01/2019

-   **Tags o Etiquetas:** cargos, federales, judiciales, jueces, justicia, magistrados, nacionales, traslados

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Relaciones con el Poder Judicial y Asuntos Penitenciarios. Oficina Decreto

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Relaciones con el Poder Judicial y Asuntos Penitenciarios. Oficina Decreto

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Relaciones con el Poder Judicial y Asuntos Penitenciarios. Oficina Decreto

-   **Grupo:** Poder Judicial

-   **Frecuencia de Actualización:** Eventual

Recursos disponibles
--------------------

### Traslados de jueces de la Justicia Federal y de la Justicia Nacional - AAAA-MM-DD

-   **Nombre:** jueces-justicia-federal-nacional-traslados-AAAA-MM-DD.csv

-   **Descripción del contenido:** se detallan los traslados de jueces de la Justicia Federal y de la Justicia Nacional

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** traslados de jueces de la Justicia Federal y de la Justicia Nacional desde el año 2003 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **justicia_federal_o_nacional_desde (int):** indica si se trata de un órgano de la justicia federal o nacional desde el cual es trasladado el magistrado. Toma los valores:

    -   Federal

    -   Nacional

-   **magistrado_nombre (string):** nombre del magistrado que es trasladado

-   **magistrado_dni (string):** DNI del magistrado que es trasladado

-   **magistrado_genero (string):** género del magistrado que es trasladado. Toma los valores:

	-   Masculino

	-   Femenino

-   **norma_numero (string):** número del decreto o resolución de traslado del magistrado

-   **norma_fecha (date):** fecha del decreto o resolución de traslado del magistrado. Formato AAAA-MM-DD

-   **norma_presidente (string):** nombre del Presidente en ejercicio a la fecha del decreto o resolución de traslado

-   **norma_ministro (string): ):** nombre del Ministro en ejercicio a la fecha del decreto o resolución de traslado

-   **fecha_traslado (date):** fecha del traslado del magistrado

-   **motivo_traslado (string):** motivo del traslado del magistrado

-   **localidad_nombre_desde (string):** nombre de la localidad de la que es trasladado el magistrado

-   **provincia_nombre_desde (string):** nombre de la provincia de la que es trasladado el magistrado

-   **organo_tipo_desde (string):** tipo de órgano del que es trasladado el magistrado. Toma los valores:

    -   Cámara

    -   Juzgado

    -   Tribunal

-   **organo_nombre_desde (string):** nombre del órgano del que es trasladado el magistrado

-   **alzada_nombre_desde (string):** nombre de la alzada de la que es trasladado el magistrado

-   **cargo_detalle_desde (string):** cargo que ocupa el magistrado antes de ser trasladado

-   **justicia_federal_o_nacional_hacia (string**): indica si se trata de un órgano de la justicia federal o nacional hacia el cual es trasladado el magistrado. Toma los valores:

    -   Federal

    -   Nacional

-   **localidad_nombre_hacia (string):** nombre de la localidad hacia la que es trasladado el magistrado

-   **provincia_nombre_hacia (string):** nombre de la provincia hacia la que es trasladado el magistrado

-   **organo_tipo_hacia (string):** tipo de órgano hacia el que es trasladado el magitrado. Toma los valores:

    -   Cámara

    -   Juzgado

    -   Tribunal

-   **organo_nombre_hacia (string):** nombre del órgano hacia el que es trasladado el magistrado

-   **alzada_nombre_hacia (string):** nombre de la alzada hacia la que es trasladado el magistrado

-   **cargo_detalle_hacia (string):** cargo que ocupa el magistrado al ser trasladado

-   **organo_provincia_desde_indec_id (int):** código de la provincia en la que se encuentra ubicado geográficamente el órgano, de la que es trasladado el magistrado, según la codificación de provincia implementada por INDEC (tener en cuenta que las jurisdicciones federales no coinciden con la división política en provincias de la República)

-   **organo_provincia_hacia_indec_id (int):** código de la provincia en la que se encuentra ubicado geográficamente el órgano, hacia la que es trasladado el magistrado, según la codificación de provincia implementada por INDEC (tener en cuenta que las jurisdicciones federales no coinciden con la división política en provincias de la República)

Notas
------

[Ley 27.275 - Derecho de Acceso a la Información Pública](http://servicios.infoleg.gob.ar/infolegInternet/anexos/265000-269999/265949/norma.htm)

Este Conjunto de datos es publicado en el Portal de Datos Abiertos de la Justicia Argentina mediante [Resolución Nº 986 del Ministerio de Justicia y Derechos Humanos](http://datos.jus.gob.ar/resoluciones/RESOL-2016-986-E-APN-MJ.pdf), del 26 de Octubre de 2016.

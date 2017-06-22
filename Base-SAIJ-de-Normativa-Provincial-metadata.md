# Base SAIJ de Normativa Provincial

Este recurso contiene las leyes, decretos leyes, textos ordenados, códigos y Constituciones publicados en el Boletín Oficial de la Provincia correspondiente. La información se actualiza diariamente y las consultas actualizadas están disponibles en [SAIJ](http:/www.saij.gob.ar/).

Características
---------------

- **Fecha de Primera Publicación:** 05/12/2016

- **Tags o Etiquetas:** leyes, decretos leyes, texto ordenado, códigos provinciales, constituciones provinciales, boletín oficial

- **Organización:** Ministerio de Justicia y Derechos Humanos. Secretaría de Planificación Estratégica. Dirección Nacional del Sistema Argentino de Información Jurídica

- **Autor:** Ministerio de Justicia y Derechos Humanos. Secretaría de Planificación Estratégica. Dirección Nacional del Sistema Argentino de Información Jurídica

- **Responsable:** Ministerio de Justicia y Derechos Humanos. Secretaría de Planificación Estratégica. Dirección Nacional del Sistema Argentino de Información Jurídica

- **Grupo:** Información Jurídica

- **Frecuencia de Actualización:** Mensualmente

Recursos disponibles
--------------------

### Base SAIJ de Normativa Provincial

- **Nombre del archivo:** base-saij-normativa-provincial.csv

- **Descripción del contenido:** Base de documentos digitales normativos provinciales: leyes, decretos leyes, textos ordenados, códigos y Constituciones publicados en el Boletín Oficial de la Provincia correspondiente.

- **Formato:** CSV delimitado por comas, codificado en UTF-8

- **Rango temporal:** Listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

- **id_norma (entero):** Identificador de la Norma

- **tipo_norma (string):** Clasificación de la norma de acuerdo a la jerarquía normativa (ej. leyes, decisiones administrativas, decretos, etc.)

- **numero_norma (string):** Número de la norma o S/N (sin número)

- **clase_norma (string):** Atributo complementario del tipo de norma (ej. Comunicaciones A B C, Resoluciones Conjuntas, etc.)

- **organismo_origen (string):** Organismo emisor de la norma

- **fecha_sancion (fecha):** Fecha que se sancionó la ley o se emitió el acto administrativo

- **numero_boletin (entero):** Número de boletín donde se publicó la norma

- **fecha_boletin (fecha):** Fecha del Boletín Oficial (BO) donde se publicó la norma

- **pagina_boletin (entero):** Número de página del boletín

- **titulo_resumido (string):** Tema específico que trata la norma

- **titulo_sumario (string):** Tema genérico que trata la norma

- **texto_resumido (string):** Sintesis de la norma (se reproduce el copete o el art. 1)

- **observaciones (string):** Anotaciones complementarias a la norma (ej. fe de erratas, aclaraciones, abrogación, etc.)

- **texto_original (string):** Link al texto original de la norma tal como fue publicado

- **texto_actualizado (string):** Link al texto actual vigente de la norma

- **modificada_por (entero):** Cantidad de normas que modifican/complementan a la presente

- **modifica_a (entero):** Cantidad de normas a las que modifica/complementa la presente

### Base Complementaria Infoleg de Normas Modificadas

- **Nombre:** base-complementaria-infoleg-normas_modificadas.csv

- **Descripción:** Base complementaria Infoleg con normas nacionales modificadas: leyes, decisiones administrativas, decretos, resoluciones, disposiciones, acordadas y todo acto administrativo publicado en la primera sección del Boletín Oficial de la República Argentina desde mayo 1997 más la normativa referenciada

- **Formato:** CSV delimitado por comas, codificado en UTF-8

- **Rango temporal:** Listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

- **id_norma_modificada (entero):** Identificador de la Norma modificada

- **id_norma_modificatoria (entero):** Identificador de la Norma modificante

- **tipo_norma (string):** Clasificación de la norma de acuerdo a la jerarquía normativa (ej. leyes, decisiones administrativas, decretos, etc.)

- **numero_norma (string):** Número de la norma o S/N (sin número)

- **clase_norma (string):** Atributo complementario del tipo de norma (ej. Comunicaciones A B C, Resoluciones Conjuntas, etc.)

- **organismo_origen (string):** Organismo emisor de la norma

- **fecha_boletin (fecha):** Fecha del Boletín Oficial (BO) donde se publicó la norma

- **titulo_sumario (string):** Tema genérico que trata la norma

- **titulo_resumido (string):** Tema específico que trata la norma

### Base Complementaria Infoleg de Normas Modificatorias

- **Nombre:** base-complementaria-infoleg-normas-modificatorias.csv

- **Descripción:** Base complementaria Infoleg con normas nacionales modificatorias: leyes, decisiones administrativas, decretos, resoluciones, disposiciones, acordadas y todo acto administrativo publicado en la primera sección del Boletín Oficial de la República Argentina desde mayo 1997 más la normativa referenciada

- **Formato:** CSV delimitado por comas, codificado en UTF-8

- **Rango temporal:** Listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

- **id_norma_modificatoria (entero):** Identificador de la norma modificatoria

- **id_norma_modificada (entero):** Identificador de la norma modificada

- **tipo_norma (string):** Clasificación de la norma de acuerdo a la jerarquía normativa (ej. leyes, decisiones administrativas, decretos, etc.)

- **numero_norma (string):** Número de la norma o S/N (sin número)

- **clase_norma (string):** Atributo complementario del tipo de norma (ej. Comunicaciones A B C, Resoluciones Conjuntas, etc.)

- **organismo_origen (string):** Organismo emisor de la norma

- **fecha_boletin (fecha):** Fecha del Boletín Oficial (BO) donde se publicó la norma

- **titulo_sumario (string):** Tema genérico que trata la norma

- **titulo_resumido (string):** Tema específico que trata la norma

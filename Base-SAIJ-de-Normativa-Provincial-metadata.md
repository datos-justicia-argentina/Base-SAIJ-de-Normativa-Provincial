# Base SAIJ de Normativa Provincial

Este conjunto de datos contiene documentos digitales normativos provinciales: leyes,decretos leyes, textos ordenados, códigos y Constituciones publicados en el Boletín Oficial de la Provincia correspondiente.

http://datos.jus.gob.ar/dataset/base-saij-de-normativa-provincial

Características
---------------

- **Fecha de Primera Publicación:** 05/12/2016

- **Tags o Etiquetas:** leyes, decretos, códigos provinciales, constituciones provinciales, boletín oficial

- **Organización:** Ministerio de Justicia. Secretaría de Justicia. Dirección Nacional del Sistema Argentino de Información Jurídica
  
- **Autor:** Ministerio de Justicia. Secretaría de Justicia. Dirección Nacional del Sistema Argentino de Información Jurídica

- **Responsable:** Ministerio de Justicia. Secretaría de Justicia. Dirección Nacional del Sistema Argentino de Información Jurídica

- **Grupo:** Información Jurídica

- **Frecuencia de Actualización:** Mensualmente

Recursos disponibles
--------------------

### Base SAIJ de Normativa Provincial

- **Nombre del archivo:** base-saij-normativa-provincial.csv

- **Descripción del contenido:** base de documentos digitales normativos provinciales: leyes, decretos leyes, textos ordenados, códigos y Constituciones publicados en el Boletín Oficial de la Provincia correspondiente

- **Formato:** CSV delimitado por comas, codificado en UTF-8

- **Rango temporal:** documentos digitales normativos provinciales desde el año 1886 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

- **provincia_nombre (string):** nombre de la provincia

- **tipo_norma (string):** clasificación de la norma de acuerdo a la jerarquía normativa (ej. leyes, decisiones administrativas, decretos, etc.) Puede tomar los siguientes valores:
    - Constitución Nacional
    - Ley
    - Decreto
    - Decreto Ley
    - Resolución
    - Disposición
    - Texto Ordenado Ley
    - Texto Ordenado Decreto
    - Circular
    - Código Civil
    - Código Civil y Comercial
    - Código Comercial
    - Código Penal
    - Código Procesal Civil Comercial
    - Código Procesal Penal
    - Código Justicia Militar
    - Código Minería
    - Código Aduanero
    - Comunicado Telefónico
    - Código Aeronáutico
    - Código Contencioso Administrativo
    - Código Fiscal
    - Ley Extranjera
    - Código Electoral
    - Ordenanza
    - Convenio Colectivo de Trabajo
    - Expediente
    - Laudo
    - Código Procesal del Trabajo
    - Norma Jurídica de Facto
    - Tratado
    - Circular Técnica
    - Resolución
    - Circular Administrativa
    - Comunicación (Banco)"
    - Directiva
    - Decreto Ordenanza
    - Convenio
    - Norma
    - Decisión Administrativa
    - Ley de Contrato de Trabajo
    - Código Alimenticio Nacional
    - Decisión del Mercosur
    - Resolución
    - Ley de Procedimiento Administrativo
    - Ley de Sociedades
    - Resolución
    - Otros
    - Resolución
    - Código Contravencional
    - Código de P. Contravencional
    - Actuación ADGA (Aduana)"
    - Dictamen Aduana
    - Dictamen de AFIP o DGI
    - Nomenclatura Común del Mercosur
    - Decreto de Necesidad y Urgencia
    - Decreto Acuerdo
    - Código Tributario
    - Acordada
    - Resolución
    - Código Procesal Minero
    - Acordada de Corte Provincial
    - Código Contencioso Administrativo y Tributario
    - Código de Faltas
    - Código Rural
    - Acuerdo
    - Resolución
    - Opinión Consultiva

- **numero_norma (string):** número de la norma o S/N (sin número)

- **estado_vigencia (string):** estado de vigencia de la norma (vigente de alcance general, derogada, individual, solo modificatoria o sin eficacia)

- **fecha (date):** fecha que se sancionó la ley o se emitió el acto administrativo

- **fecha_publicacion (date):** fecha del Boletín Oficial provincial donde se publicó la norma

- **nombre_norma (string):** nombre coloquial de la norma y/o nomenclatura conforme digesto provincial

- **titulo_resumido (string):** descripción específica del contenido de la norma

- **titulo_sumario (string):** descripción genérica del contenido de la norma

- **informacion_digesto (string):** información proveniente de las consolidaciones por digesto a la norma

- **texto_actualizado (string):** link al texto actual vigente de la norma

- **provincia_id (string):** código de la provincia en la que se publicó la norma según la codificación de provincia implementada por INDEC (este campo está disponible desde agosto de 2018)

Notas
-----

[Ley 27.275 - Derecho de Acceso a la Información Pública]( http://servicios.infoleg.gob.ar/infolegInternet/anexos/265000-269999/265949/norma.htm)

Este Conjunto de datos es publicado en el Portal de Datos Abiertos de la Justicia Argentina mediante [Resolución Nº 106 del Ministerio de Justicia](http://datos.jus.gob.ar/resoluciones/RESOL-2017-106-APN-MJ.pdf), del 2 de Febrero de 2017.

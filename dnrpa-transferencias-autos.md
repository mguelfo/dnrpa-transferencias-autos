DNRPA. Transferencias de Autos
=======================================

En este cuerpo de datos se detallan los datos de vehículos y primer titular de transferencias de automotores. El trámite de transferencia del automotor se realiza en los Registros Seccionales de la Propiedad del Automotor y Créditos Prendarios dependientes de la Dirección Nacional de Registros Nacionales de la Propiedad Automotor y Créditos Prendarios. Se consideran automotores: automóviles, camiones, inclusive los llamados tractores para semirremolque, camionetas, rurales, jeeps, furgones de reparto, ómnibus, microómnibus y colectivos, sus respectivos remolques y acoplados, todos ellos aun cuando no estuvieran carrozados.

http://datos.jus.gob.ar/dataset/transferencias-de-autos

Características
---------------

-   **Fecha de Primera Publicación:** 26/01/2018

-   **Tags o Etiquetas:** autos, registración, registros seccionales, titulares, transferencias, trámites, vehículosa, automotores, DNRPA

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Dirección Nacional de Registros Nacionales de la Propiedad Automotor y Créditos Prendarios

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Dirección Nacional de Registros Nacionales de la Propiedad Automotor y Créditos Prendarios

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Dirección Nacional de Registros Nacionales de la Propiedad Automotor y Créditos Prendarios

-   **Grupo:** Sistema Registral

-   **Frecuencia de Actualización:** Mensualmente

Recursos disponibles
--------------------

### DNRPA. Transferencia de autos AAAA-MM

-   **Nombre del archivo:** transferencias-automotores-AAAA-MM.csv

-   **Descripción del contenido:** se detalla la cantidad de autos 0km inscriptos, por año, mes y provincia

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** desde el 01-01-2018 a la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **tramite\_tipo (string):** tipo de inscripción realizada. Puede referir a una inscripción realizada mediante Formulario 01 (autos nacionales o importados), Formulario 05 (automotores subastados) o automotores clásicos.

-   **tramite\_fecha (date):** fecha del trámite en la cual se perfecciona el trámite. Formato AAAA-MM-DD.

-   **fecha\_inscripcion\_inicial (date):** fecha de inscripción inicial. Formato AAAA-MM-DD.

-   **registro\_seccional\_codigo (int):** código del Registro Seccional en que se efectuó el trámite. Los códigos de Registros Seccionales están organizados por provincia y competencia.

-   **registro\_seccional\_descripcion (string):** nombre del Registro Seccional en que se efectuó el trámite. Generalmente nombre refiere a la localización del Registro Seccional. No siempre coincide con la localidad del domicilio del titular del automotor.

-   **registro\_seccional\_provincia (string):** provincia donde se localiza el Registro Seccional en que se inscribió el trámite. Corresponde asimismo a la provincia del domicilio del primer titular de la inscripción o de la guarda habitual del dominio.

-   **automotor\_origen (string):** corresponde al origen del vehículo. Puede tomar los valores I Importado, N Nacional o P Protocolo 21, que se rigen por los aranceles de los automotores nacionales pero se inscriben con el certificado de importación.

-   **automotor\_tipo\_codigo (string):** código del tipo del automotor.

-   **automotor\_tipo\_descripcion (string):** descripción del tipo del automotor. Puede tomar los valores sedán, pick-up, camión, semirremolque, todo terreno, minibús, etc.

-   **automotor\_marca\_codigo (string):** código de la marca del automotor.

-   **automotor\_marca\_descripcion (string):** descripción de la marca del automotor.

-   **automotor\_modelo\_codigo (string):** código del modelo del automotor.

-   **automotor\_modelo\_descripcion (string):** descripción del modelo del automotor.

-   **automotor\_uso\_codigo (string):** código de uso del automotor.

-   **automotor\_uso\_descripcion (string):** descripción del uso declarado del automotor. Puede tomar los valores

    -   Privado

    -   Oficial

    -   No declarado

-   **titular\_tipo\_persona (string):** tipo de persona del primer titular declarado. Puede tomar los valores

    -   Física

    -   Jurídica

    -   No identificada

-   **titular\_domicilio\_localidad (string):** localidad del domicilio del primer titular declarado.

-   **titular\_domicilio\_provincia (string):** provincia del domicilio del primer titular declarado.

-   **titular\_sexo (string):** sexo del primer titular declarado. Puede tomar los valores

    -   Masculino (en caso de persona física)

    -   Femenino (en caso de persona física)

    -   No identificado (en caso de persona física)
    
    -   No aplica (en caso de persona jurídica)
    

-   **titular\_año\_nacimiento (int):** sexo del primer titular declarado.

-   **titular\_sexo (string):** sexo del primer titular declarado.

-   **titular\_pais\_nacimiento (string):** país de nacimiento del primer titular declarado.<span id="notas" class="anchor"><span id="estad%C3%ADstica-de-transferencias-de-au" class="anchor"></span></span>

-   **titular\_porcentaje\_titularidad (int):** porcentaje de titularidad.

### Notas

La actividad registral de los automotores está regulada por el Régimen Jurídico del Automotor, el Digesto de normas técnico-registrales y el Reglamento Interno de Normas Orgánico - Funcionales y Disposiciones Modificatorias. Esta documentación se encuentra disponible en la sección normativa de la [*Página oficial de la DNRPA*](http://www.dnrpa.gov.ar/portal_dnrpa/regimenj2.php)Para consultar más datos referidos a los Registros Seccionales, remitirse al [*Listado de Registros Seccionales de la DNRPA*](http://datos.jus.gob.ar/dataset/listado-de-registros-seccionales-de-la-dnrnpa).

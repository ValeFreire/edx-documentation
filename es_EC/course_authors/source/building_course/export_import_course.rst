.. _Exporting and Importing a Course:

#####################################
Exportar e Importar Cursos
#####################################

Tu puedes :ref:`Exportar un Curso` y :ref:`ImportarCurso` através de la sessión de estudio.

.. _Export a Course:

***************
Exportar Curso
***************

Hay varias razones por las cuales se desee exportar un curso:

* Guardar trabajo
* Editar el XML en el curso directamente
* Crear una copia de seguridad del curso, que se puede importar, en caso que se desee revertir el curso de nuevo a un estado anterior
* Crear una copia del curso que posteriormente puede importar a otra instancia y personalizar
* Compartir con otro instructor para otra clase


Al exportar un curso, cree un archivo **.tar.gz* que incluya los siguientes datos curso:

* El contenido del curso (todas las secciones, subsecciones y unidades)
* Estructura del curso
* Los problemas individuales
* Las páginas
* Activos del curso
* Configuración del curso   

 
.. warning::

	Cuendo se exporta un curso, al exportar un curso, tenga en cuenta que la información tal como llaves API MATLAB, pasaportes LTI, cadenas secretas token y URL almacenados están incluidos en los datos
        exportados. Si comparte los  archivos exportados, también puede intercambiar información sensible o licencias específicas

La siguiente información no es exportada con el curso

* Datos de Usuarios 
* Datos de los integrantes del Curso
* Información de Discusiones
* Certificados

Exportar un Curso:
 
#. Desde el menú **Herramientas**, seleccionar  **Exportar**.
#. Click **Exportar contenido del Curso**.

Cuando se haya exportado completamente, se puede acceder al archivo .tar.gz desde la computadora.


.. _Import a Course:

*************** 
Importar Curso
***************

.. warning::

	El contenido del curso es remplazado en su totaledad en el contenido del curso importado.
	**No se podra deshacer un curso que haya sido importado**. Se recomienda que primero se exporte el curso actual, así se obtendrá un respaldo de esto.
 
Hay varias razones para querer importar un curso:

* Ejecutar una nueva versión del curso existente
* Remplazar el archivo existente 
* Cargar un curso generado fuera de la sessión de estudio


El archivo del curso que se desee importar deben estar en .tar.gz (esto es, un archivo .tar comprimido en un zip de GNU )
Este archivo .tar.gz debe contener un archivo curso.xml en un directorio del curso. El archivo tar.gz debe tener un nombre similar como el directorio del curso.
Este también puede tener otros archivos.

Si el curso utiliza estructuras de disposición de legado, es posible que no pueda editar el curso en el estudio, aunque es probable que aparezcan correctamente en el Edge. 
Para asegurarse que el  curso es completamente editable, asegúrese de que todo el  material este embebido  en una unidad.

El proceso de importación tiene cinco etapas. Durante las dos primeras etapas, debe permanecer en la página en Importar. 
Puede salir de esta página después de que se haya  completado la importación. 
Se recomienda, sin embargo, que no se realicen cambios importantes en el curso hasta que la operación de importación se ha completado.
 
 
Importar Curso:
 
#. Desde el menú **Herramients**, seleccionar  **Importar**.
#. Click **Seleccionar archivo a Importar**.
#. Localizar el archivo que desee, luego hacer click **Abrir **.
#. Click **Remplazar el curso**.


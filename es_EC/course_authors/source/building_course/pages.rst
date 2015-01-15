.. _Adding Pages to a Course:

###########################
Añadir paginas al Curso
###########################


*******************
Vista General
*******************

Por defecto, los cursos tienen las siguientes páginas:

* Courseware
* Info. Curso
* Discusiones
* Wiki
* Progreso

No se puede renombrar, reordenar o remover esas paginas.

Se pueden añadir páginas al curso.Cada página aparcerá en la barra de navegación del curso.

Por ejemplo, la siguiente barra de navegación incluye las páginas predeterminadas, así como el ** Horario del curso ** y ** Suplementos & Instructor de blog **. 

.. image:: ../Images/page_bar_lms.png
 :alt: Image of the page bar in the LMS

Puede crear otras paginas para las políticas de calificación del curso, diapositivas del curso, u otros propositos.Mś ejemplos de páginas que pueden ser agragadas son:

* Google calendar, para ser embebido en el código.  

* Un calendario HTML dinamico, usando en la plantilla :ref:`Codigo HTML dinámico para Horarios`.

* Un  hangout instantánea.  Para más información ver :ref:`Google Instant Hangout`.

Ver:

* :ref:`Añadir Página`
* :ref:`Mostrar u ocultar el Curso Página Wiki`
* :ref:`Reordenar Páginas`
* :ref:`Borrar Páginas`
* :ref:`Código para el horario HTML dinámico`


.. _`Añadir Página`:

********************
Añadir nueva Página
********************

#. Es estudio, desde el meú de  **Contenidos** , seleccione **Páginas**. 

  .. image:: ../Images/pages_page.png
   :alt: Image of the Pages screen


2. Click en **Añadir nueva página**. Una página con el título **Vacio** Es añadida a la lista:

  .. image:: ../Images/pages_empty.png
   :alt: Image of the Pages screen with a new Empty page

3. Click en **Editar**. El editor editor se abre.  

  .. image:: ../Images/pages_editor.png
   :alt: Image of the Page editor

4. Ingresar texto para el curso. Para mayor información ver :ref:`Opciones para la Edición de Componentes HTML` acerca del uso del editor.
#. Click en  **Ajustes** editar el  **Nombre a Visualizar**. El nombre a visualizar es el nombre de la página que será visible para los estudiantes en el curso.
#. Click en  **Guardar**. 

La nueva página es inmediatamente disponibles para los estudiantes, si el curso ha empezado.

.. _Mostrar u ocultar el Curso Página Wiki:

************************************************
Mostrar u ocultar el Curso Página Wiki
************************************************

Por defecto, el curso incluye una página Wiki. Estudiantes y staff del curso pueden usar la Wiki para publicar contenido y comentar en otros contenidos.

Si ud. no quiere usar la Wiki en el curso, se puede ocultar la página.

El ícono del ojo en el objeto Wiki indica que la página Wiki es visible en el curso:

.. image:: ../Images/pages_wiki_on.png
 :alt: Image of the Pages page with the Wiki made visible

Click en el ícono del ojo para poder ocultar la Wiki de la página. El cambio de ícono:

.. image:: ../Images/pages_wiki_off.png
 :alt: Image of the Pages page with the Wiki made visible

Haga clic de nuevo para hacer la página Wiki visible.

.. note:: Contenido permanece en el Wiki cuando se oculta la página. Por ejemplo, si un estudiante marca un tema Wiki, luego la página Wiki es ocultada, 
el estuduante puede aun usar el bookmar para accedet al tema en el Wiki. Todos los contenidos que estan previamente publicados en el Wiki queda disponible después de ocultar la página wiki, y cualquier
 estudiante e ingresados pueden acceder al contenido si conocen la URL.
 

.. _Reordenar Páginas:

******************
Reordenar Páginas
******************


Puede cambiar el orden de las páginas del curso arrastrando y soltando las páginas a diferentes lugares. 

Para mover una página, coloque el cursor sobre el elemento en la parte derecha de la fila de la página hasta que el puntero del ratón cambia a una flecha de cuatro puntas. 
Luego, haga clic y arrastre la página a la ubicación que desee.

.. note:: No se puede cambiar el orden de los Materiales Formativos, Información del Curso, Discusión, Wiki, y las páginas de progreso que su curso incluye por defecto.

.. _Borrar Páginas:

****************
Borrar Páginas
****************

Borrar una página que esta previamente añadida, haga clic en el icono de papelera en la fila de la página. Se le solicitará que confirme la eliminación.

.. _Código para el horario HTML dinámico:

*************************************
Código para el horario HTML dinámico
*************************************

Se puede usar el siguiente código en la página para proporcionar una programación HTML dinámico en su curso.

.. code-block:: html


	<div class= "syllabus">

	<table style="width: 100%">
 		<col width="10%">
 		<col width="15%">
  		<col width="10%">
  		<col width="30%">
  		<col width="10%">
  		<col width="15%">
  		<col width="10%">
  
	<!-- Headings -->
 		 <thead>
    			<td class="day"> Wk of </td>
   			<td class="topic"> Topic </td>
   			<td class="reading"> Read </td>
    			<td class="video"> Lecture Sequence </td>	
    			<td class="slides"> Slides </td>
    			<td class="assignment"> HW/Q </td>
			<td class="due"> Due </td>
  		</thead>
  
	<!-- Week 1 Row 1 -->
 		 <tr class="first">
   			<td class="day">10/22</td>
			<td class="topic">Topic 1</td>
			<td class="reading">Ch. 1</td>
    			<td class="video"><a href="#">L1: Title</a></td>
    			<td class="slides"><a href="#">L1</a></td>
    			<td class="assignment"><a href="#">HW 1</a></td>
    			<td class="due">11/04</td>
  		</tr>
  
	<!-- Week 1 Row 2 -->
    		<tr>
    			<td class="day"> </td>
    			<td class="topic"></td>
    			<td class="reading"></td>
    			<td class="video"><a href="#">L2: Title</a></td>
    			<td class="slides"><a href="#">L2</a></td>
    			<td class="assignment">     </td>
   			 <td class="due">      </td>
  		</tr>

   		 <tr> <td class="week_separator" colspan=7> <hr/> </td> </tr>
  
	<!-- Week 2 Row 1 -->
 		 <tr>
    			<td class="day">10/29</td>
    			<td class="topic">Topic 2</td>
    			<td class="reading">Ch. 2</td>
    			<td class="video"> <a href="#">L3: Title<a></td>
   			 <td class="slides"><a href="#">L3</a></td>
    			<td class="assignment"><a href="#">Quiz 1</a></td>
    			<td class="due">11/11</td>
 		 </tr>
  
	<!-- Week 2 Row 2 -->
 		<tr>
  			<td class="day"></td>
    			<td class="topic"></td>
    			<td class="reading"></td>
    			<td class="video"><a href="#">L4: Title</a></td>
    			<td class="slides"><a href="#">L4</a> </td>
    			<td class="assignment"></td>
    			<td class="due"></td>
  		</tr>
  		<tr> <td class="week_separator" colspan=7> <hr/> </td> </tr>
  
	<!-- Week 3 Row 1 -->
  		<tr>
    			<td class="day">11/05</td>
    			<td class="topic">Topic 3</td>
    			<td class="reading">Ch. 3</td>
    			<td class="video"><a href="#">L5: Title</a></td>
    			<td class="slides"><a href="#">L5 </a></td>
    			<td class="assignment"><a href="#">HW 2</a></td>
    			<td class="due">11/18 </td>
  		</tr>
  
	<!-- Week 3 Row 2 -->
		<tr>
    			<td class="day"> </td>
    			<td class="topic"> </td>
    			<td class="reading"></td>
    			<td class="video"><a href="#">L6: Title</a></td>
    			<td class="slides"><a href="#">L6 </a></td>
    			<td class="video"></td>
    			<td class="assignment"></td>
    			<td class="due"></td>
  		</tr>
  		<tr> <td class="week_separator" colspan=7> <hr/> </td> </tr>
  
	<!-- Week 4 Row 1 -->
  		<tr>
    			<td class="day">11/12</td>
    			<td class="topic">Topic 4</td>
    			<td class="reading">Ch. 4</td>
    			<td class="video"><!--<a href="#">L7: Title</a>--> L7: Title</td>
    			<td class="slides"><!--<a href="#">L7</a>-->L7</td>
    			<td class="assignment"><!--<a href="#">Quiz 2</a>-->Quiz 2</td>
    			<td class="due"> 11/25 </td>
  		</tr>
  
	<!-- Week 4 Row 2 -->
    		<tr>
    			<td class="day"></td>
    			<td class="topic"></td>
    			<td class="reading"></td>
    			<td class="video"><!--<a href="#">L8: Title</a>-->L8: Title</td>
    			<td class="slides"><!--<a href="#">L8</a>-->L8</td>
    			<td class="assignment"></td>
    			<td class="due"></td>
  		</tr>
  		<tr> <td class="week_separator" colspan=7> <hr/> </td> </tr>
  
	<!-- Week 5 Row 1 -->
  		<tr>
    			<td class="day">11/19</td>
    			<td class="topic">Topic 5</td>
    			<td class="reading">Ch. 5</td>
    			<td class="video"><!--<a href="#">L9: Title</a>-->L9: Title</td>
    			<td class="slides"><!--<a href="#">L9</a>-->L9</td>
    <			td class="assignment"><!--<a href="#">HW 3</a>-->HW 3</td>
    			<td class="due"> 12/02 </td>
  		</tr>
  
	<!-- Week 5 Row 2 -->
   		<tr>
    			<td class="day"></td>
    			<td class="topic"></td>
    			<td class="reading"></td>
    			<td class="video"><!--<a href="#">L10: Title</a>-->L10: Title</td>
    			<td class="slides"><!--<a href="#">L10</a>-->L10 </td>
    			<td class="assignment"></td>
    			<td class="due"></td>
  		</tr>
  		<tr> <td class="week_separator" colspan=7> <hr/> </td> </tr>
  
	<!-- Week 6 Row 1 -->
  		<tr>
    			<td class="day">11/26</td>
    			<td class="topic">Topic 6</td>
    			<td class="reading">Ch. 6</td>
    			<td class="video"><!--<a href="#"><L11: Title</a>-->L11: Title </td>
    			<td class="slides"><!--<a href="#">L11</a>-->L11</td>
    			<td class="assignment"><!--<a href="#">HW 4</a>-->HW 4</td>
    			<td class="due">12/09</td>
  		</tr>
  
	<!-- Week 6 Row 2 -->
    		<tr>
			<td class="day"> </td>
    			<td class="topic"> </td>
    			<td class="reading"></td>
    			<td class="video"><!--<a href="#">L12: Title</a>-->L12: Title</td>
    			<td class="slides"><!--<a href="#">L12</a>-->L12</td>
    			<td class="assignment"></td>
    			<td class="due">      </td>
		</tr>

	</table>
	</div>


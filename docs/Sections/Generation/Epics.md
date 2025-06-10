---
id: Epics
title: Generación de épicas
sidebar_position: 3
---

Para acceder a la generación de épicas, de click en la opción "**_Generate Epics_**" dentro de la vista "**_Generate_**"
![Seleccionar generate epics](img/epics/VistaSelectGenerateEpics.png) 

Alternativamente, si ya está dentro de la pantalla de requerimientos puede dar click sobre el botón "**_Epics_**" en la cintilla de opciones.
![Vista cintilla epics desde requerimientos](img/epics/VistaSelectEpicsReq.png)

Una vez seleccionado, llegará a la vista de "**_Generate Epics_**". Aquí usted dispondrá de los requerimientos seleccionados previamente que servirán como base para generar las épicas mediante inteligencia artificial.
![Vista generate epics](img/epics/VistaGenerateEpics.png)

:::info

Si desea cambiar los requerimientos selccionados, necesita repetir el [proceso de selección de requerimientos en la pantalla de generación de requerimientos](Requirements/#seleccionar-requerimientos)

:::

## Importar requerimientos

Si no cuenta con requerimientos seleccionados, puede importar todos los requerimientos guardados en la base de datos dando click en el botón "**_Import Requirements_**". Esto abrirá una ventana emergente para confirmar la importación de todos los requerimientos disponibles para el proyecto, de click en "**_Import_**" para confirmar.

Botón "**_Import Requirements_**"
![Vista import requirements](img/epics/VistaImportReq.png)

Confirmación para importar requerimientos
![Vista confirmar importación](img/epics/VistaImportReqConf.png)

## Generar épicas

### Generar épicas con inteligencia artificial

Para generar épicas usando la inteligencia artificial, asegúrese de tener **requerimientos seleccionados** ya que estos servirán como entrada para el proceso de generación. Una vez tenga los requerimientos necesarios, de click en "**_Generate Epics_**"
![Vista con requerimientos listos para generar épicas](img/epics/VistaBotonGenerateEpics.png)

Tras esto se abrirá una ventana emergente pidiendo la confirmación ya que generar nuevas épicas sobreescribirá las que ya se tenían hechas, de click en "**_Generate_**" para confirmar la generación. A continuación tendrá que esperar mientras la inteligencia artificial procesa y genera las épicas
![Vista confirmación de generación de épicas](img/epics/VistaConfirmaciónGenReq.png)

Una vez concluido el proceso podrá ver las épicas generadas en base a los requerimientos seleccionados. En la lista generada usted podrá **[seleccionar las épicas](#seleccionar-épicas)** con las que esté conforme o editar las épicas para ajustarlas.
![Vista con las épicas generadas](img/epics/VistaEpicsGenerated.png)

#### Volver a generar épicas con inteligencia artificial

Puede volver a generar las épicas generadas por la inteligencia artificial para obtener épicas diferentes si siente que las generadas no cumplen con lo que busca. Para esto de click en el botón "**_Regenerate_**". Esto abrirá una ventana emergente para que confirme si usted desea proceder, de click en "**_Generate_**" para volverlas a generar.

Botón "**_Regenerate_**"
![Vista botón regenerate épicas](img/epics/VistaEpicsRegenerate.png)

Mensaje de confirmación
![Vista popup confirmación regenerar épicas](img/epics/VistaEpicsRegenerateConf.png)

:::warning Cuidado

Volver a generar las épicas hará que se sobreescriba la lista presentada actualmente y no podrá recuperarlas

:::

### Agregar épicas manualmente

Puede agregar épicas del proyecto de manera manual, para esto de click en "**_Edit View_**" y después en "**_+ Add Manually_**"; esto abrirá un formulario para añadir los detalles de la épica. Una vez haya terminado de agregar los detalles de click en "**_Add_**".

Vista de edición y opción de añadir épica
![Vista edición y añadir épica](img/epics/VistaAgregarEpica.png)

Vista del formulario para añadir épica
![Vista formulario para añadir épica](img/epics/VistaAgregarEpicaForm.png)

## Editar épicas

Puede editar las épicas creadas desde la vista de edición. Para esto será necesario que de click en "**_Edit View_**", después de esto de click sobre el ícono de lápiz para abrir el formulario de edición donde podrá añadir a cuáles requerimientos esta asociado; una vez haya terminado de editar la información de la épica de click en "**_Save_**"

Vista de edición de épicas:
![Vista de edición épicas](img/epics/VistaEdicionEpicas.png)

Formulario de edición y botón "**_Save_**"
![Vista formulario de edición y botón save](img/epics/VistaFormEdicionEpicas.png)

## Eliminar épicas

Puede eliminar épicas desde la vista de edición. Haga click en "**_Edit View_**" y de click sobre el ícono de lápiz para abrir el formulario de edición, una vez ahí de click en "**_Delete_**" para eliminar la épica deseada.

Vista de edición de épicas:
![Vista de edición épicas](img/epics/VistaEdicionEpicas.png)

Formulario de edición y botón "**_Delete_**"
![Vista formulario de edición y botón delete](img/epics/VistaFormEdicionEpicas.png)

:::warning Cuidado

Al eliminar una épica no es posible recuperarla

:::

## Seleccionar épicas

Cuando tenga épicas agregadas, selecciónelas dando click sobre ellas o puede decidir seleccionar todas haciendo click en el botón "**_Select all_**".

Para deshacer la selección de épicas de click sobre la épica a eliminar de la selección.

Selección de épicas
![Vista selección individual de épicas](img/epics/VistaSelectionEpicas.png)

Botón "**_Select All_**"
![Vista botón select all épicas](img/epics/VistaSelectAllEpicas.png) 

## Guardar épicas

Cuando esté conforme con su selección de épicas generadas, guárdelas dando click en el botón "**_Save_**"; esto abrirá una ventana emergente preguntando por confirmación, de click en "**_Save_**". Asegúrese que todas las épicas que desea conservar estén seleccionadas correctamente.

Botón "**_Save_**"
![Vista botón save épicas](img/epics/VistaSaveEpicas.png)

Mensaje de confirmación para guardar épicas
![Vista confirmación save épicas](img/epics/VistaSaveEpicasConf.png)

Mensaje de éxito 

:::info Importante

Recuerde que solo se guardarán las épicas seleccionadas

:::

## Eliminar todas las épicas y requerimientos

Puede usar el botón "**_Clear_**" para eliminar todas las épicas y requerimientos, independientemente de si están seleccionados o no. Al dar click en el botón "**_Clear_**" se le mostrará una ventana emergente para confirmar la eliminación de todas las épicas y requerimientos, de click en "**_Confirm_**" para eliminar todo el contenido.

Botón "**_Clear_**"
![Vista botón clear épicas](img/epics/VistaEpicasClear.png)

Vista confirmación de eliminación de todas las épicas y requerimientos
![Vista confirmación clear épicas y requerimientos](img/epics/VistaConfirmacionClearEpicas.png)

:::warning Cuidado

Eliminar todas las épicas y requerimientos es un proceso no reversible y toda la información no guardada se perderá. Puede guardar las épicas y requerimientos si desea conservarlos.

:::
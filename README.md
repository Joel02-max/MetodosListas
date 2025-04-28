MetodosListas
Una aplicación de escritorio en C# Windows Forms para gestionar una lista de elementos mediante agregar y eliminar ítems de una lista.

Descripción
Esta aplicación permite al usuario:

Agregar elementos a una lista.

Eliminar elementos seleccionados de la lista.

Ver en pantalla los elementos almacenados.

Está diseñada con una interfaz simple y amigable para el usuario, configurada manualmente en el código (ConfigurarInterfaz), sin necesidad de un diseñador visual (Drag & Drop).

Estructura del Proyecto
Form1.cs:

Contiene la lógica de la interfaz.

Define métodos para agregar, eliminar y actualizar la lista de elementos.

Controles Utilizados:

TextBox (txtElemento): Para ingresar el nuevo elemento.

ListBox (lstElementos): Para mostrar los elementos actuales.

Button (btnAgregar): Para agregar un nuevo elemento.

Button (btnEliminar): Para eliminar el elemento seleccionado.

Label (lblTitulo): Para el título de la lista.

Requisitos
Visual Studio 2019, 2022 o superior.

.NET Framework 4.7.2 o superior.

Sistema operativo Windows.

Instalación y ejecución
Clona el repositorio o copia los archivos a tu máquina.

Abre el proyecto en Visual Studio.

Asegúrate de que Form1.cs esté configurado como formulario principal en Program.cs.

Ejecuta el proyecto (F5).

Uso de la Aplicación
Escribe un elemento en el campo de texto.

Haz clic en Agregar para insertarlo en la lista.

Selecciona un elemento de la lista y haz clic en Eliminar para quitarlo.

Si intentas agregar un campo vacío o eliminar sin selección, recibirás un mensaje de advertencia.

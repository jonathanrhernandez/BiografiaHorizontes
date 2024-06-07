# General

###### Diagrama de comonentes

[Imagen](.\Documentation\ComponentsDiagram.jpg)

- **AppComponent**: Es el componente principal que engloba toda la aplicación. Actúa como el punto de entrada principal y contiene todos los demás componentes de la aplicación.
- **HeaderComponent**: Muestra el encabezado de la página, que va a incluir el título del catálogo de biografías y el menú de navegación.
- **BiographyListComponent**: Es responsable de mostrar la lista completa de biografías disponibles en el catálogo. Este componente puede mostrar una serie de BiographyItemComponentes que representan cada biografía en la lista.
- **FooterComponent**: Muestra el pie de página de la aplicación, que incluye información de contacto.
- **SearchComponent**: Permite a los usuarios buscar biografías ingresando el nombre de una persona. Cuando se realiza una búsqueda, este componente filtra la lista de biografías para mostrar solo las coincidencias de nombres.
- **BiographyItemComponent**: Representa un elemento individual en la lista de biografías. Muestra información básica sobre cada biografía, como el nombre de la persona, foto y una breve descripción.
- **BiographyDetailComponent**: Muestra los detalles completos de una biografía específica cuando se selecciona desde la lista. Proporciona una vista detallada de la biografía, que puede incluir información como la fecha de nacimiento, lugar de nacimiento, ocupación y una descripción completa de la vida y logros de la persona.
- **ImageComponent**: Maneja la carga y visualización de imágenes relacionadas con las biografías. Puede mostrar imágenes de personas famosas asociadas con cada biografía.
- **CardComponent**: Un componente de tarjeta genérico que puede mostrar contenido diverso. En este contexto, puede ser utilizado para mostrar miniaturas de biografías en la lista de biografías o en otros lugares donde se necesiten representaciones visuales de la información.
- **AddBiographyComponent**: Este componente proporciona la funcionalidad para que los usuarios puedan agregar nuevas biografías al catálogo. incluye un formulario donde los usuarios ingresen la información relevante sobre la persona, como el nombre, la fecha de nacimiento, la ocupación, etc.
- **NotFoundComponent**: Este componente se muestra cuando un usuario intenta acceder a una página que no existe o no se encuentra. Proporciona una página de error amigable para informar al usuario sobre el problema y sugerir posibles acciones que puedan tomar.

###### Diseño

[Imagen](./Documentation/Design.jpg)

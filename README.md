Guía Interactiva D&D Revisión 2024
¡Bienvenido/a a la Guía Interactiva de Dungeons & Dragons Revisión 2024! Este proyecto es una página web diseñada para ser un recurso completo tanto para jugadores nuevos como para veteranos que exploran los cambios y novedades de la última revisión de D&D (a menudo comparada con la 5ª Edición de 2014).

🌟 Características Principales
Esta guía no es solo un documento estático, sino una herramienta interactiva que incluye:

Comparativa Detallada 2014 vs. 2024:

Análisis de la filosofía general de la revisión.

Cambios fundamentales en la creación de personajes (Especies, Trasfondos, Clases, Dotes).

Actualizaciones en las reglas del juego (Combate, Magia, etc.).

Guías para Nuevos Jugadores:

Guía de Combate: Explicaciones detalladas del flujo del combate, acciones, reacciones, tipos de ataque, daño, puntos de golpe y cobertura, presentadas en un formato de acordeón fácil de navegar.

Guía de Magia: Fundamentos del lanzamiento de conjuros, componentes, duración, concentración, listas de conjuros (Arcana, Divina, Primordial) y lanzamiento ritual, también en formato de acordeón.

Análisis Detallado por Clase:

Secciones dedicadas a los cambios específicos de cada clase (actualmente incluye Pícaro, Hechicero y Druida, con espacio para expandir).

Presentado en una interfaz de pestañas para una fácil consulta.

Filtro de búsqueda para encontrar rápidamente la clase deseada.

Asistentes IA con Gemini API:

Generador de Ideas para Trasfondos: Introduce palabras clave y la IA te ayudará a desarrollar una historia base para tu personaje, sugiriendo Rasgos, Ideales, Vínculos y Defectos.

Consulta de Reglas IA: Formula preguntas específicas sobre las reglas de la Revisión 2024 y obtén explicaciones generadas por la IA.

Interfaz de Usuario Moderna y Funcionalidades Avanzadas:

Modo Oscuro "Nocturno": Un tema oscuro agradable a la vista (tonos azulados/grises) que se puede activar y cuya preferencia se guarda en Firestore (o localStorage como fallback) para persistencia entre sesiones.

Botón "Volver Arriba": Facilita la navegación en páginas largas.

Menú de Navegación Lateral (Sidebar): Accesible en dispositivos móviles para una navegación fluida por todas las secciones.

Diseño Responsivo: Adaptado para una correcta visualización en diferentes tamaños de pantalla.

Animaciones Sutiles: Efectos de aparición gradual y transiciones para una experiencia de usuario más pulida.

🛠️ Tecnologías Utilizadas
HTML5: Estructura semántica del contenido.

CSS3: Estilos personalizados, incluyendo:

Variables CSS para temificación (modo claro/oscuro).

Flexbox y Grid para layout.

Transiciones y animaciones.

Tailwind CSS: Framework CSS de utilidad para un desarrollo rápido y responsivo.

JavaScript (Vanilla JS): Para toda la interactividad, incluyendo:

Manejo del DOM.

Lógica del modo oscuro, sidebar, acordeones, pestañas, filtro.

Animaciones de scroll.

Llamadas a la API de Gemini.

Firebase (Google):

Firestore: Para persistencia de la preferencia del modo oscuro del usuario.

Authentication: Para identificación de usuarios (anónima por defecto) y así poder guardar sus preferencias.

Gemini API (Google AI): Para las funcionalidades de los asistentes IA (generación de trasfondos y consulta de reglas).

Lucide Icons: Para algunos iconos de la interfaz.

🚀 Cómo Empezar / Uso
Clona este repositorio (o descarga los archivos).

Abre el archivo index.html (o el nombre que tenga tu archivo principal) en tu navegador web preferido.

¡Explora las diferentes secciones y utiliza las herramientas interactivas!

Nota sobre Firebase y Gemini API:

Para que la persistencia del tema en Firestore y las funcionalidades de la API de Gemini funcionen completamente si clonas el proyecto, necesitarás configurar tu propio proyecto de Firebase y obtener tus propias claves de API para Gemini.

En el código actual, las variables __firebase_config y __initial_auth_token se esperan del entorno de ejecución (como Canvas de Google). Si ejecutas el HTML localmente sin este entorno, la persistencia del tema recurrirá a localStorage y las llamadas a la API de Gemini podrían necesitar una clave de API válida insertada directamente en el script (lo cual no se recomienda para producción pública). La variable geminiApiKey en el script también está pensada para ser manejada por el entorno o dejada vacía si el modelo lo permite.

🎯 Objetivos del Proyecto
Proporcionar un recurso claro y accesible sobre los cambios de la Revisión 2024 de D&D.

Ayudar a los nuevos jugadores a entender las mecánicas básicas de combate y magia.

Ofrecer herramientas creativas (como el generador de trasfondos IA) para enriquecer la experiencia de juego.

Demostrar la integración de funcionalidades modernas de UI/UX y APIs de IA en una aplicación web estática/dinámica.

🤝 Contribuciones
Las contribuciones son bienvenidas. Si tienes ideas para mejorar la guía, añadir más clases, refinar las explicaciones o corregir errores, por favor, siéntete libre de abrir un issue o enviar un pull request.

📜 Licencia
Este proyecto se distribuye bajo la licencia MIT (puedes añadir un archivo LICENSE.md con el texto de la licencia MIT si lo deseas).

Esperamos que esta guía te sea de gran utilidad en tus aventuras por los mundos de Dungeons & Dragons.
¡Que tus dados rueden siempre a tu favor!

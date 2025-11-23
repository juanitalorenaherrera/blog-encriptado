📝 README.md — Blog de Sueños Encriptados
🔐 Blog de Sueños Encriptados — Guarda tus sueños con AES-GCM

Este proyecto es una mini-app web que funciona como un diario de sueños cifrado.
Todo se guarda solo en tu navegador, usando AES-GCM y una frase secreta que nunca viaja a ningún servidor.
Tus sueños se vuelven un tesoro escondido, guardado en tu bóveda personal como si fueras un hacker-poeta del futuro. ✨

🚀 Características principales
🔒 Seguridad real (pero sencilla)

Cifrado AES-GCM 256 bits usando Web Crypto API.

Derivación de clave mediante PBKDF2 + SHA-256.

Nada se sube a servidores: todo vive en localStorage.

Puedes exportar e importar tu bóveda como archivo .json cifrado.

🧠 Crea y administra tus sueños

Editor para escribir títulos, etiquetas y el contenido del sueño.

Sistema de etiquetas (tags) separado por comas.

Entradas se guardan cifradas automáticamente.

Fechas, búsqueda, copia al portapapeles, edición y eliminación.

🗄️ Bóveda cifrada

Bloquear y desbloquear con tu frase secreta.

Estado visible: 🔒 / 🔓

Contador de entradas.

Buscador para encontrar sueños por texto, título o etiquetas.

📤 Importar / Exportar

Exporta toda tu bóveda encriptada.

Importa otra bóveda (ideal para respaldos, migraciones o viajes entre dispositivos).

💣 Zona peligrosa

Opción para borrar toda la bóveda desde localStorage.

🎨 Diseño

Estilo cyber-místico con colores oscuros y brillos suaves.

Paneles con efecto glassmorphism.

Tipografías cómodas y minimalistas.

Interfaz adaptable (responsive) para celulares.

🛠️ Tecnologías utilizadas

HTML5

CSS puro (sin frameworks)

JavaScript Vanilla

Web Crypto API (AES-GCM, PBKDF2)

localStorage para persistencia

📂 Estructura del Proyecto
blog.html


Todo el proyecto está contenido en un solo archivo.

Incluye:

Estilos

Lógica del cifrado

Sistema de UI

Render de entradas

Importación y exportación

Búsqueda, edición y manejo de eventos

🧪 Cómo usarlo

Descarga o abre blog.html.

Escribe tu frase secreta y pulsa Desbloquear.

Si es tu primera vez, se creará una bóveda nueva automáticamente.

Escribe un título, etiquetas y tu sueño.

Haz clic en Guardar encriptado.

Usa la barra de búsqueda para filtrar tus sueños.

Exporta para respaldar tu bóveda.

Bloquea la bóveda cuando termines.

🔥 Ideas para mejorarlo

Modo oscuro/claro seleccionable.

Sincronización cifrada a través de un archivo remoto opcional.

Edición real que reemplace la entrada en vez de crear una nueva versión.

Vista tipo “timeline”.

Estadísticas de sueños: palabras, estados de ánimo, frecuencia.

Autoguardado.

👤 Autoría

Proyecto creado por Juanis, programadora jr con un pie en la lógica y otro en lo onírico. 🌙💻

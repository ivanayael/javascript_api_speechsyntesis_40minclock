#⏱️ Speech Synthesis 40-Min Clock
Una aplicación web interactiva que funciona como un temporizador de 40 minutos, utilizando la Web Speech API para anunciar por voz el tiempo transcurrido o avisos específicos. Ideal para sesiones de estudio, entrenamientos o gestión de bloques de tiempo (estilo Pomodoro extendido).

# 🚀 Características
Cronómetro de cuenta regresiva: Configurado específicamente para ciclos de 40 minutos.
Síntesis de Voz (TTS): Utiliza la SpeechSynthesisUtterance de JavaScript para dar avisos auditivos.
Interfaz Simple: Diseño minimalista y funcional centrado en la usabilidad.
Sin Dependencias: Escrito en Vanilla JavaScript, HTML5 y CSS3. No requiere instalaciones pesadas.

# 🛠️ Tecnologías utilizadas

HTML5: Estructura de la aplicación.
CSS3: Estilos y diseño responsivo.
JavaScript (ES6+): Lógica del temporizador y manejo de la Web Speech API.

# 📦 Instalación y Uso
No necesitas configurar un entorno de servidor complejo. Simplemente sigue estos pasos:

Clona el repositorio:

Bash
git clone https://github.com/ivanayael/javascript_api_speechsyntesis_40minclock.git
Navega a la carpeta del proyecto:

Bash
cd javascript_api_speechsyntesis_40minclock
Abre el archivo principal: Simplemente abre index.html en tu navegador favorito.

#🎙️ Cómo funciona la síntesis de voz
La aplicación detecta las voces disponibles en tu sistema operativo y navegador. Al llegar a hitos de tiempo específicos (ej. "quedan 10 minutos", "tiempo cumplido"), el navegador generará una locución automática.

# JavaScript
// Ejemplo del núcleo de la lógica de voz
const mensaje = new SpeechSynthesisUtterance("Han pasado 40 minutos");
window.speechSynthesis.speak(mensaje);

#📄 Licencia
Este proyecto está bajo la licencia MIT. Puedes usarlo, modificarlo y distribuirlo libremente.

#👤 Autor
Desarrollado por Ivan Ayael.

#💡 Sugerencia de mejora para tu repo:

[] Permitir al usuario elegir el idioma de la voz.
[] Ajustar el intervalo de tiempo (no solo 40 minutos).
[] Añadir un botón de "Pausa" y "Reinicio".

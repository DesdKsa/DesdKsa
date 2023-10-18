# Bienvenidos a DesdKsa Market 👋

🚀 DesdKsa Market

## Sobre Nosotros

DesdKsa Market es una aplicación web CMS construida en PHP que busca impulsar el desarrollo y la contribución a través de la creación de complementos. Nuestro objetivo es crear un ambiente de colaboración donde los desarrolladores pueden construir, compartir y aprender juntos.

### Características Destacadas
- 🌐 Plataforma de código abierto
- 🤝 Fomenta la colaboración
- 🛠️ Crea y comparte complementos
- 📚 Recursos y tutoriales
- 🌟 Comunidad activa

## Hola Mundo! 👋

```javascript
function saludar() {
  let mensaje = "DesdKsa Market dice 'Hola mundo';";
  let i = 0;
  let velocidad = 100; // Velocidad de escritura (en milisegundos)

  function escribirMensaje() {
    if (i < mensaje.length) {
      document.getElementById("saludo").innerHTML += mensaje.charAt(i);
      i++;
      setTimeout(escribirMensaje, velocidad);
    }
  }

  escribirMensaje();
}

saludar();

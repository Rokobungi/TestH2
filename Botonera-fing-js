// Definir una función que aplique los estilos de la botonera mediante clases
function aplicarEstilosBotoneraFING() {
  const hojaEstilo = document.createElement('style');
  hojaEstilo.textContent = `
    .fing-nav {
      display: flex;
      justify-content: center;
      background-color: #394049;
      padding: 1rem 0;
    }
    .fing-nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      padding: 0.5rem 1rem;
      display: inline-block;
    }
    .fing-menu-item {
      position: relative;
      margin: 0 20px;
    }
    .fing-submenu {
      display: none;
      position: absolute;
      top: 100%;
      left: 0;
      background-color: #00A499;
      min-width: 160px;
      z-index: 1;
    }
    .fing-submenu a {
      display: block;
      padding: 0.5rem 1rem;
      color: white;
      text-decoration: none;
    }
    .fing-submenu a:hover {
      background-color: #394049;
    }
    .fing-menu-item:hover .fing-submenu {
      display: block;
    }
  `;
  document.head.appendChild(hojaEstilo);
}

// Ejecutar al cargar la página
document.addEventListener("DOMContentLoaded", () => {
  aplicarEstilosBotoneraFING();
});

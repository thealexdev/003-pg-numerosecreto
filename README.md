# Número Secreto

Juego web de lógica en el que debes adivinar un número aleatorio entre 1 y 10. La interfaz utiliza una temática espacial y se adapta a pantallas de escritorio y móviles.

## Funcionalidades

- Generación aleatoria de un número secreto entre 1 y 10.
- Tres intentos para descubrir el número.
- Pistas para indicar si el número secreto es mayor o menor.
- Mensajes visuales de victoria y fin del juego.
- Validación de números y advertencias para campos vacíos o valores inválidos.
- Reinicio de partida al finalizar el juego.

## Tecnologías

- HTML, CSS y JavaScript.
- [Vite](https://vite.dev/) para el entorno de desarrollo y la compilación.
- [Bootstrap 5](https://getbootstrap.com/) y Bootstrap Icons mediante CDN.

## Requisitos

- Node.js 20.19+ o 22.12+.
- npm.

## Instalación y uso

```bash
npm install
npm run dev
```

Vite mostrará la URL local para abrir el juego en el navegador.

## Scripts

| Comando | Descripción |
| --- | --- |
| `npm run dev` | Inicia el servidor de desarrollo. |
| `npm run build` | Genera la versión de producción en `dist/`. |
| `npm run preview` | Sirve localmente la compilación de producción. |

## Cómo jugar

1. Escribe un número entre 1 y 10.
2. Pulsa **Intentar**.
3. Usa la pista para decidir tu siguiente intento.
4. Adivina el número antes de agotar los tres intentos.
5. Pulsa **Nuevo juego** para iniciar otra partida.

## Estructura

```text
css/        Estilos de la aplicación
imgs/       Recursos visuales
js/main.js  Lógica del juego y de interfaz
index.html  Estructura de la página
```

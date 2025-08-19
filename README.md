# GuitarLA

Tienda virtual de guitarras desarrollada con **React** y **Vite**.

## Características

- Catálogo de guitarras con imágenes, descripción y precio.
- Carrito de compras con persistencia en localStorage.
- Estilos personalizados y uso de Bootstrap.
- Animaciones y diseño responsivo.

## Estructura del proyecto

```
├── public/
│   └── img/           # Imágenes de guitarras y recursos
├── src/
│   ├── components/    # Componentes React (Header, Guitar)
│   ├── data/          # Base de datos simulada (db.js)
│   ├── assets/        # Recursos adicionales
│   ├── index.css      # Estilos globales
│   ├── App.jsx        # Componente principal
│   └── main.jsx       # Punto de entrada
├── index.html         # HTML principal
├── package.json       # Dependencias y scripts
└── vite.config.js     # Configuración de Vite
```

## Instalación

1. Clona el repositorio:
   ```sh
   git clone https://github.com/tu-usuario/GuitarLa.git
   cd GuitarLa
   ```

2. Instala las dependencias:
   ```sh
   npm install
   ```

## Uso

- Inicia el servidor de desarrollo:
  ```sh
  npm run dev
  ```
- Abre [http://localhost:5173](http://localhost:5173) en tu navegador.

## Scripts disponibles

- `npm run dev` — Ejecuta el proyecto en modo desarrollo.
- `npm run build` — Compila la aplicación para producción.
- `npm run preview` — Previsualiza la versión de producción.
- `npm run lint` — Ejecuta ESLint.

## Créditos

- Imágenes de guitarras: [public/img](public/img)
- Basado en [Vite](https://vitejs.dev/) y [React](https://react.dev/)

## Licencia

MIT
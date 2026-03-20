# 🛒 Carrito de Compras — React App

Aplicación de e-commerce SPA desarrollada con **React 19** y **Vite**, como proyecto final del curso *React.js* dictado por [Sergie Code](https://www.youtube.com/@SergieCode) en **Digital House**.

> 🔗 **[Ver demo en vivo](https://proyecto-final-carrito-compras-dh.netlify.app/)**

---

## ✨ Funcionalidades

- 🛍️ Catálogo de productos consumido desde [Fake Store API](https://fakestoreapi.com/)
- 🔍 Filtrado de productos por categoría mediante React Router
- ➕ Agregar y eliminar productos del carrito
- 🔢 Actualización de cantidad por producto
- 💰 Cálculo dinámico del total del carrito
- 🔔 Notificaciones con **SweetAlert2** al agregar/eliminar productos
- 🧠 Estado global del carrito manejado con **Context API** + `useReducer`
- 📱 Diseño responsivo con **Bootstrap** y estilos personalizados
- 🛒 Ícono de carrito con contador usando **Material UI Icons**

---

## 🧰 Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| [React 19](https://react.dev/) | Librería principal de UI |
| [Vite](https://vitejs.dev/) | Bundler y servidor de desarrollo |
| [React Router DOM v7](https://reactrouter.com/) | Navegación entre páginas |
| [Context API](https://react.dev/reference/react/useContext) + `useReducer` | Estado global del carrito |
| [Bootstrap](https://getbootstrap.com/) | Estilos y layout responsivo |
| [Material UI](https://mui.com/) | Íconos de la interfaz |
| [SweetAlert2](https://sweetalert2.github.io/) | Alertas y notificaciones |
| [Fake Store API](https://fakestoreapi.com/) | Fuente de datos de productos |

---

## 🪝 Hooks utilizados

- `useState` — estado local de componentes
- `useEffect` — fetch de productos al montar el componente
- `useReducer` — lógica de acciones del carrito (agregar, eliminar, actualizar cantidad)
- `useContext` — acceso al estado global del carrito desde cualquier componente

---

## 🚀 Instalación y uso local

### Prerequisitos

- Node.js v18 o superior
- npm

### Pasos

```bash
# 1. Clonar el repositorio
git clone https://github.com/natanaelDominguez28/proyecto-final-carrito-compras.git
cd proyecto-final-carrito-compras

# 2. Instalar dependencias
npm install

# 3. Iniciar servidor de desarrollo
npm run dev
```

Luego abrí [http://localhost:5173](http://localhost:5173) en tu navegador.

### Scripts disponibles

| Comando | Descripción |
|---|---|
| `npm run dev` | Inicia el servidor de desarrollo |
| `npm run build` | Genera el build de producción |
| `npm run preview` | Previsualiza el build de producción |
| `npm run lint` | Ejecuta ESLint |

---

## 📁 Estructura del proyecto

```
src/
├── components/        # Componentes reutilizables (Navbar, ProductCard, etc.)
├── context/           # Context y Reducer del carrito
├── pages/             # Vistas principales (Home, Carrito, etc.)
├── styles/            # Estilos para las Cards y el NavBar
├── CarritoApp.jsx     # Configuración de rutas
└── main.jsx           # Punto de entrada
```

---

## 👨‍💻 Autor

**Natanael Dominguez**
📌 Analista Programador Universitario

[![GitHub](https://img.shields.io/badge/GitHub-natanaelDominguez28-181717?logo=github)](https://github.com/natanaelDominguez28)


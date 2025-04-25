
# 🍌 Banana Ripeness Predictor - Frontend

Este es el proyecto **frontend** de una aplicación web que utiliza **Machine Learning** para predecir el **nivel de madurez de un plátano** a partir de imágenes tomadas diariamente. El sistema busca apoyar investigaciones o desarrollos agrícolas mediante una interfaz clara y sencilla que permita visualizar los resultados del modelo entrenado.

El frontend está desarrollado con **Angular 19**, y se comunica con un backend en **Node.js** (disponible en otro repositorio) para el procesamiento de imágenes y la ejecución del modelo de aprendizaje automático.

---

## 🧠 ¿Cómo funciona?

1. El usuario sube una imagen de un plátano tomada en condiciones controladas (una imagen por día).
2. La imagen se envía al backend, que ejecuta un modelo de ML previamente entrenado.
3. El modelo predice el **estado** del plátano (por ejemplo: Bueno, maduro, Malogrado).
4. La predicción se visualiza en la interfaz con indicadores gráficos y texto.

---

## 🚀 Tecnologías utilizadas

- **Angular 19** – Framework para el desarrollo de aplicaciones web modernas.
- **TypeScript** – Lenguaje base de Angular.
- **RxJS** – Programación reactiva para el manejo de datos asíncronos.
- **SCSS** – Para estilos más organizados y mantenibles.
- **API REST** – Comunicación con el backend en Node.js.

---

## 📁 Estructura del proyecto

```
banana-ripeness-frontend/
├── src/
│   ├── app/
│   │   ├── components/        # Componentes visuales reutilizables
│   │   ├── pages/             # Páginas principales de la app
│   │   ├── services/          # Servicios para consumir la API
│   │   ├── models/            # Interfaces y tipos
│   │   └── app.module.ts      # Módulo raíz de Angular
├── assets/                    # Archivos estáticos
├── environments/              # Variables de entorno (desarrollo/producción)
└── angular.json               # Configuración del proyecto
```

---

## ⚙️ Instalación y uso

### 1. Clona el repositorio

```bash
git clone https://github.com/tu-usuario/banana-ripeness-frontend.git
cd banana-ripeness-frontend
```

### 2. Instala las dependencias

```bash
npm install
```

### 3. Ejecuta el proyecto en desarrollo

```bash
ng serve
```

Abre tu navegador en `http://localhost:4200/` para ver la aplicación.

---

## 🌐 Comunicación con el backend

Este frontend se conecta a un backend en Node.js mediante peticiones HTTP. Asegúrate de que el backend esté corriendo y que la URL base esté configurada correctamente en el archivo de entorno (`src/environments/environment.ts`).

---

## 📝 Estado del proyecto

- [x] Estructura básica de Angular 19
- [x] Carga de imágenes
- [x] Envío al backend
- [ ] Visualización de resultados con gráficos
- [ ] Historial de predicciones por espécimen
- [ ] Autenticación de usuarios (futuro)

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si quieres colaborar, por favor abre un *issue* o haz un *fork* del proyecto y envía un *pull request*.

---

## 📄 Licencia

Este proyecto se distribuye bajo la licencia [MIT](LICENSE).

# Numiacity - Salud y Farmacia

Un sitio web responsivo inspirado en Farmacity que ofrece servicios de farmacia y salud integral.

## 🚀 Características

- **Diseño Responsivo**: Optimizado para dispositivos móviles, tablets y desktop
- **Interfaz Moderna**: Diseño limpio y profesional con Tailwind CSS
- **Formulario de Reserva**: Sistema de reserva de turnos con integración a API
- **Botón "Estoy Aquí"**: Notificación directa al sistema de colas
- **Categorías de Productos**: Organización clara de productos de salud
- **Servicios de Salud**: Información sobre vacunación, gabinetes de salud y más

## 🛠️ Tecnologías Utilizadas

- **React 18**: Framework de JavaScript para la interfaz de usuario
- **Tailwind CSS**: Framework de CSS para diseño responsivo
- **Axios**: Cliente HTTP para llamadas a la API
- **Lucide React**: Iconos modernos y consistentes
- **React Router**: Navegación entre páginas

## 📦 Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/numiacity.git
cd numiacity
```

2. Instala las dependencias:
```bash
npm install
```

3. Inicia el servidor de desarrollo:
```bash
npm start
```

4. Abre [http://localhost:3000](http://localhost:3000) en tu navegador.

## 🔧 Configuración

### Variables de Entorno

El proyecto utiliza las siguientes configuraciones de API:

- **Endpoint**: `https://filavirtual2.debmedia.com/api/v1/queue/11393/branch/10588/enqueue`
- **API Token**: `iyAUHKKJ2NTsxf4sAH1OWm3fljRsThvxF0kbCGWe`

### Estructura del Proyecto

```
numiacity/
├── public/
│   └── index.html
├── src/
│   ├── App.jsx          # Componente principal
│   ├── index.jsx        # Punto de entrada
│   └── index.css        # Estilos globales
├── package.json
├── tailwind.config.js   # Configuración de Tailwind
└── README.md
```

## 🎯 Funcionalidades Principales

### 1. Formulario de Reserva de Turnos
- Campos: Nombre, Apellido, DNI, Email, Teléfono
- Validación de campos requeridos
- Integración con API de reservas
- Feedback visual de éxito/error

### 2. Botón "Estoy Aquí"
- Envía notificación directa al sistema
- Usa datos predefinidos para pruebas
- Feedback inmediato al usuario

### 3. Categorías de Productos
- Farmacia
- Nutrición y Deportes
- Electrosalud
- Nutrición Infantil
- Bienestar Sexual
- Medicamentos

### 4. Servicios de Salud
- Reserva de turnos online
- Gabinetes de salud
- Vacunación
- Medicina del viajero
- Cannabis medicinal

## 🎨 Diseño

El sitio utiliza un diseño moderno con:

- **Paleta de Colores**: Azul primario (#0ea5e9) con grises neutros
- **Tipografía**: Inter font family
- **Componentes**: Cards, botones, formularios consistentes
- **Responsive**: Mobile-first approach

## 📱 Responsive Design

El sitio está optimizado para:
- **Mobile**: 320px - 768px
- **Tablet**: 768px - 1024px
- **Desktop**: 1024px+

## 🔌 API Integration

### Endpoint de Reserva
```javascript
POST /api/v1/queue/11393/branch/10588/enqueue
Host: filavirtual2.debmedia.com
x-api-token: iyAUHKKJ2NTsxf4sAH1OWm3fljRsThvxF0kbCGWe
Content-Type: application/json

{
    "firstName": "Juan",
    "lastName": "Perez",
    "dni": "12345678",
    "email": "mail@mail.com",
    "phone": "12345678"
}
```

## 🚀 Despliegue

### Build para Producción
```bash
npm run build
```

### Despliegue en GitHub Pages
1. Configura GitHub Pages en tu repositorio
2. El build se generará automáticamente en la carpeta `build/`
3. Configura el dominio personalizado si es necesario

## 🤝 Contribución

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 📞 Contacto

- **Email**: info@numiacity.com
- **Teléfono**: 0800-123-4567
- **Horarios**: Lun a Dom 8:00 - 22:00

## 🙏 Agradecimientos

- Inspirado en el diseño de [Farmacity](https://www.farmacity.com/salud-y-farmacia)
- Iconos proporcionados por [Lucide React](https://lucide.dev/)
- Framework CSS por [Tailwind CSS](https://tailwindcss.com/) 

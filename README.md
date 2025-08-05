# 🏴‍☠️ One Piece API & AI ChatBox

<div align="center">
  <img src="https://i.imgur.com/9WK4N1x.png" alt="One Piece Logo" width="300" height="200"/>
  
  ### ⚔️ API completa de One Piece con ChatBox inteligente powered by Gemini 2.0
  
  [![Next.js](https://img.shields.io/badge/Next.js-14+-000000?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/)
  [![NestJS](https://img.shields.io/badge/NestJS-10+-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)](https://nestjs.com/)
  [![TypeScript](https://img.shields.io/badge/TypeScript-5+-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
  [![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com/)
  [![Gemini](https://img.shields.io/badge/Gemini%202.0-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://deepmind.google/technologies/gemini/)
  
  <br/>
  
  [![Creado por](https://img.shields.io/badge/Creado%20por-Alberto%20Marin-blue?style=flat-square&logo=github)](https://github.com/albertomarin)
  [![Licencia](https://img.shields.io/badge/Licencia-MIT-green?style=flat-square)](LICENSE)
  [![En Desarrollo](https://img.shields.io/badge/Estado-En%20Desarrollo-orange?style=flat-square)](https://github.com/albertomarin/onepiece-api)
  
</div>

---

## 🎯 ¿Qué es este proyecto?

Una **API REST completa** del universo de One Piece que incluye información detallada sobre personajes, frutas del diablo, arcos narrativos, tripulaciones y mucho más. Además, cuenta con un **chatbox inteligente** que utiliza **Gemini 2.0** para responder todas tus dudas sobre el mundo de los piratas más famoso del anime/manga.

### ✨ Características Principales

- 🔍 **API REST completa** con datos exhaustivos de One Piece
- 🤖 **ChatBox AI** powered by Gemini 2.0 para consultas inteligentes
- 📱 **Frontend responsive** con Next.js 14 y App Router
- ⚡ **Backend robusto** con NestJS y TypeScript
- 🗄️ **Base de datos escalable** con Supabase
- 🔐 **Autenticación segura** y gestión de usuarios
- 📊 **Panel de administración** para gestionar contenido
- 🎨 **UI/UX moderna** con Tailwind CSS

---

## �️ Mi RoadMap de Desarrollo

<div align="center">

### 📚 Stack Tecnológico que estoy dominando

| Tecnología | Estado | Descripción | Recursos |
|------------|--------|-------------|----------|
| ![TypeScript](https://img.shields.io/badge/TypeScript-🚀-3178C6?style=flat-square&logo=typescript) | **Completado** | Fundamentos y tipos avanzados | [Mi progreso](./docs/typescript-progress.md) |
| ![React](https://img.shields.io/badge/React/Next.js-⚡-000000?style=flat-square&logo=next.js) | **En progreso** | Next.js 14, App Router, Server Components | [Mi progreso](./docs/nextjs-progress.md) |
| ![NestJS](https://img.shields.io/badge/NestJS-🔥-E0234E?style=flat-square&logo=nestjs) | **Siguiente** | API REST, Guards, Interceptors | [Planificado](./docs/nestjs-roadmap.md) |
| ![Supabase](https://img.shields.io/badge/Supabase-📊-3FCF8E?style=flat-square&logo=supabase) | **Siguiente** | Database, Auth, Real-time | [Planificado](./docs/supabase-roadmap.md) |
| ![Gemini](https://img.shields.io/badge/Gemini%202.0-🤖-4285F4?style=flat-square&logo=google) | **Final** | AI Integration, Prompt Engineering | [Planificado](./docs/gemini-integration.md) |

</div>

---

## 🛠️ Arquitectura del Proyecto

<div align="center">

```mermaid
graph TB
    A[👤 Usuario] --> B[🖥️ Next.js Frontend]
    B --> C[🚀 NestJS API]
    C --> D[📊 Supabase Database]
    C --> E[🤖 Gemini 2.0 AI]
    
    B --> F[🎨 Tailwind CSS]
    C --> G[🔐 JWT Auth]
    D --> H[📋 One Piece Data]
    E --> I[💬 ChatBox Responses]
```

</div>

---

## 🏴‍☠️ Funcionalidades de la API

### 👥 Personajes
- **Mugiwara no Ichimi** (Tripulación del Sombrero de Paja)
- **Yonko** y sus tripulaciones
- **Marines** y Almirantes
- **Shichibukai** y ex-miembros
- **Revolucionarios**
- **Supernovas**

### 🍎 Frutas del Diablo
- **Paramecia** - Poderes sobrenaturales
- **Zoan** - Transformaciones animales
- **Logia** - Control de elementos naturales
- **Frutas Especiales** y **Despertares**

### 🗺️ Arcos y Sagas
- **East Blue Saga**
- **Alabasta Saga**
- **Water 7 Saga**
- **Thriller Bark**
- **Summit War Saga**
- **New World Saga**
- **Wano Country Arc**

### 🏝️ Islas y Ubicaciones
- **Grand Line**
- **New World**
- **Red Line**
- **Islas específicas** con detalles geográficos

---

## 🤖 ChatBox Inteligente

El chatbox utiliza **Gemini 2.0** para proporcionar respuestas contextualizadas sobre:

- 💡 **Consultas sobre personajes**: "¿Cuáles son los poderes de Luffy?"
- 🔍 **Búsquedas específicas**: "Muéstrame todas las frutas Logia"
- 📊 **Comparaciones**: "¿Quién es más fuerte entre Zoro y Sanji?"
- 🎯 **Teorías y análisis**: "¿Qué sabemos sobre el One Piece?"
- 📚 **Cronología**: "¿En qué orden ocurrieron los arcos?"

---

## 🚀 Instalación y Configuración

### Prerrequisitos
```bash
Node.js >= 18.0.0
npm >= 9.0.0
Git
Cuenta de Supabase
API Key de Google Gemini
```

### 1. Clonar el Repositorio
```bash
git clone https://github.com/albertomarin/onepiece-api.git
cd onepiece-api
```

### 2. Configurar Frontend (Next.js)
```bash
cd frontend
npm install
cp .env.example .env.local
# Configurar variables de entorno
npm run dev
# 🌐 Frontend: http://localhost:3000
```

### 3. Configurar Backend (NestJS)
```bash
cd backend
npm install
cp .env.example .env
# Configurar variables de entorno
npm run start:dev
# 🚀 API: http://localhost:3001
```

### 4. Configurar Base de Datos (Supabase)
```bash
# Ejecutar migraciones
npm run db:migrate
npm run db:seed
# 📊 Base de datos lista con datos de One Piece
```

---

## � Estructura del Proyecto

```
onepiece-api/
├── �️ frontend/                  # Next.js App
│   ├── app/                     # App Router
│   ├── components/              # Componentes UI
│   ├── hooks/                   # Custom Hooks
│   ├── lib/                     # Utilidades
│   └── styles/                  # Tailwind CSS
├── 🚀 backend/                   # NestJS API
│   ├── src/
│   │   ├── characters/          # Módulo personajes
│   │   ├── devil-fruits/        # Módulo frutas
│   │   ├── arcs/                # Módulo arcos
│   │   ├── chatbox/             # Módulo AI Chat
│   │   └── auth/                # Autenticación
│   └── prisma/                  # Schema de BD
├── � database/                  # Scripts de Supabase
│   ├── migrations/              # Migraciones
│   └── seeds/                   # Datos iniciales
├── 🤖 ai/                       # Configuración Gemini
└── 📁 docs/                     # Documentación
    ├── api/                     # Docs de API
    └── roadmap/                 # Mi progreso
```

---

## � Endpoints Principales

### 👥 Personajes
```typescript
GET    /api/characters           // Todos los personajes
GET    /api/characters/:id       // Personaje específico
GET    /api/characters/crew/:id  // Por tripulación
POST   /api/characters           // Crear personaje (Admin)
```

### 🍎 Frutas del Diablo
```typescript
GET    /api/devil-fruits         // Todas las frutas
GET    /api/devil-fruits/:type   // Por tipo (Paramecia, Zoan, Logia)
GET    /api/devil-fruits/:id     // Fruta específica
```

### 🤖 ChatBox AI
```typescript
POST   /api/chat/ask            // Enviar pregunta
GET    /api/chat/history        // Historial de chat
```

---

## 💭 Ejemplos de Uso del ChatBox

<details>
<summary><strong>🔍 Consulta sobre Personajes</strong></summary>

**Usuario:** "¿Cuáles son todos los poderes de Monkey D. Luffy?"

**Gemini AI:** "Luffy posee la fruta Gomu Gomu no Mi (ahora conocida como Hito Hito no Mi, Modelo: Nika), que le otorga:
- Cuerpo elástico como goma
- Inmunidad a ataques eléctricos
- Gears (Técnicas especiales):
  - Gear Second: Acelera su circulación
  - Gear Third: Infla sus huesos
  - Gear Fourth: Combina Haki y elasticidad
  - Gear Fifth: Despertar de su fruta (Forma Nika)
- Haki del Rey, Observación y Armamento dominados"

</details>

<details>
<summary><strong>⚔️ Comparaciones de Poder</strong></summary>

**Usuario:** "¿Quién ganaría entre Zoro y Mihawk actualmente?"

**Gemini AI:** "Actualmente, Dracule Mihawk seguiría siendo superior a Roronoa Zoro:
- Mihawk: El espadachín más fuerte del mundo
- Zoro: Ha crecido enormemente en Wano, pero aún aspira a superar a Mihawk
- Diferencias clave: Experiencia, dominio del Haki superior en Mihawk
- Predicción: Zoro está cerca, pero Mihawk mantiene la ventaja por ahora"

</details>

---

## 🎨 Capturas de Pantalla

<div align="center">
  <img src="https://via.placeholder.com/800x400/FF6B35/FFFFFF?text=Frontend+Next.js+%F0%9F%8F%B4%E2%80%8D%E2%98%A0%EF%B8%8F" alt="Frontend" width="45%"/>
  <img src="https://via.placeholder.com/800x400/E0234E/FFFFFF?text=NestJS+API+%E2%9A%A1" alt="Backend API" width="45%"/>
</div>

<div align="center">
  <img src="https://via.placeholder.com/800x400/3FCF8E/FFFFFF?text=Supabase+Database+%F0%9F%93%8A" alt="Database" width="45%"/>
  <img src="https://via.placeholder.com/800x400/4285F4/FFFFFF?text=Gemini+ChatBox+%F0%9F%A4%96" alt="AI ChatBox" width="45%"/>
</div>

---

## 📈 Mi Progreso Personal

### ✅ Completado
- [x] **TypeScript fundamentals** - Tipos, interfaces, generics
- [x] **React basics** - Hooks, componentes, estado
- [x] **Tailwind CSS** - Utility-first CSS framework

### 🔄 En Progreso
- [ ] **Next.js 14** - App Router, Server Components, SSR
- [ ] **React avanzado** - Context, Reducers, Performance
- [ ] **Diseño de UI/UX** - Componentes reutilizables

### 📋 Próximamente
- [ ] **NestJS** - Modules, Controllers, Services, Guards
- [ ] **Supabase** - Database design, Auth, Real-time
- [ ] **Gemini 2.0** - AI Integration, Prompt Engineering
- [ ] **DevOps** - Docker, CI/CD, Deployment

---

## 📞 Contacto y Seguimiento

<div align="center">

### 👨‍💻 Alberto Marin - Pirate Developer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alberto-marin-morales/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/albertomarin)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/albertomarin)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alberto.marin@example.com)

</div>

### �️ Sígueme en mi aventura
- 📝 **Blog de desarrollo**: Documentando cada paso de mi aprendizaje
- 🎥 **Videos de progreso**: Mostrando el desarrollo en tiempo real
- 💬 **Streams de código**: Programando en vivo este proyecto
- 📊 **Updates semanales**: Mi progreso con cada tecnología

---

## 🤝 Contribuciones

¿Eres fan de One Piece y desarrollador? ¡Únete a la tripulación!

1. 🍴 Fork el proyecto
2. 🌟 Crea tu rama (`git checkout -b feature/new-character`)
3. � Commit tus cambios (`git commit -m 'Add Gear 5 Luffy'`)
4. 📤 Push a la rama (`git push origin feature/new-character`)
5. 🔄 Abre un Pull Request

---

## 📜 Licencia

Este proyecto está bajo la Licencia MIT. Ver [LICENSE](LICENSE) para más detalles.

*Nota: Este es un proyecto de fans. One Piece pertenece a Eiichiro Oda y Shueisha.*

---

<div align="center">
  
  **🏴‍☠️ ¿Listo para navegar por el Grand Line del desarrollo? ¡Zarpa conmigo! ⚓**
  
  ![One Piece](https://media.giphy.com/media/MP1kygLQzjCve/giphy.gif)
  
  <sub>Hecho con ❤️ y mucho café ☕ por [Alberto Marin](https://github.com/albertomarin)</sub>
  <sub>*"I'm gonna be King of the Developers!"* 👑</sub>
  
</div>

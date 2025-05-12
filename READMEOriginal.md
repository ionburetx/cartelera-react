# Cartelera de películas 

## Situación profesional

Crear desde cero una web-cartelera tipo `Netflix` para ver una lista películas calasificadas, y sus detalles básicos: título, descripción y cartel.

## Profesión:

Desarollador Frontend.

## Competencias

- Crear una interfaz de usuario web adaptable, utilizando un framemework profesional: [React](https://es.react.dev/)

- Herramienta profesional de construcción FrontEnd: [Vite](https://vite.dev/)

- Gestionar el estado de la app, utilizando una librería profesional: [Zustand](https://zustand-demo.pmnd.rs/) + [Axios](https://axios-http.com/es/docs/intro)

- Gestionar los estilos de cada componente de forma aislada: [Tailwind](https://tailwindcss.com/)

- Testing profesional: [Testing Library](https://testing-library.com/) + [Playwright](https://playwright.dev/) + [MSVjs](https://mswjs.io/)

## Necesidad

Necesitamos compartir con el público la lista de películas de un servicio de streaming ficticio.

## Modalidad pedagógica

Trabajo en equipo

## Modalidad de evaluación

Revisión de entregables por parte del profesorado.

## Entregables

1. Investigación:
    1. Todos (~20h):
        - Vite: configuración básica
        - Componentes funcionales + JSX
        - Hooks useState + useEffect
        - Formularios - validaciones
        - Routing básico react-router-dom
        - Vitest Setup inicial

    2. Equipo 1 - Componentes + Vitest (~30h)
        - Tailwind CSS
        - Patrones de componentes: Props children, composición
        - Testing. Pruebas de renders e interacciones básicas (@testing-library/user-event)

        Entrega: Librearía de 3-4 componentens reutilizables (Button, Card, Modal) con tests de vitest al 70% de cobertura.

    3. Equipo 2 - Estado + API (~30h)
        - Zustand (alternativa simple a Redux) para gestión de estados
        - Axios (alternativa evolucionadad de fetch) para recuperación de datos
        - Testing: Pruebas stores (Zuzstand), y mock de APIs en tests (msw)
        
        Entrega: App de ToDOs con estado global (Zustand) y obtencion de datos mockeados (JSON Server), con tests al 60% de cobertura
    
    4. Equipo 3 - Navegación + Autenticación
        - Auth0 + Google Sign-In
        - rutas protegidas (<ProtectedRoute>)
        - Testing Mock de Auth0 en tests y pruebas a rutas protegidas
  
        Entrega: App simple con login social (Auth0+Google) + 1 ruta protegida testeada al 50%
    
    5. Equipo 4 - Testing avanzado + CI
        - Coverage reports (--coverage)
        - Mock de módulos complejos
        - CI básico: Correr tests con GitHub Actions
        - Estratégia de testing: qué probar y qué no probar
        - Tests E2E, con Playwright

        Entrega: Manual de testing para el resto de equipos, configuración de CI de GitHub y demo de Playwright

3. Historias de usuario que contemplan los requisitos de la actividad.

4. Prototipo de baja fidelidad (boceto).

5. Prototipo de alta fidelidad y guía de estilo (penpot).

6. HTML y recursos (imágenes y css) en un repositorio github personal.

7. Documento de tareas repartidas.

8. Documento de equipo que detalle:
  - Nombre
  - Componentes con su rol
  - Normas internas
  - Objetivos de equipo
  - Compromisos del equipo
  - Reflexión:
    - ¿Qué hemos logrado?
    - ¿Cómo lo hemos hecho?
    - ¿Qué no hemos logrado? 
    - ¿Qué mejoraríamos?
    - ¿Cómo lo mejoraríamos?
    - ¿Qué debemos seguir haciendo?
    - ¿Qué debemos empezar a hacer?
    - ¿Qué debemos hacer mejor?
    - ¿Qué debemos dejar de hacer?
    - ¿Qué hemos aprendido?


Para hacer la entrega, el alumnado deberá publicar el enlace al repositorio en el canal 06-cartelera de discord.

## Criterios de rendimiento

- Toda la funcionalidad cubierta.
- Código correctamente indentado y limpio.
- Todos los tags correctamente abiertos/cerrados (https://validator.w3.org/).
- Comentarios de código donde se necesiten.
- Ficheros no-html en directorios aparte.
- Se valorará si se puede ver el avance a través de los commits.
- El conjunto de las tareas han de cubrir la funcionalidad requerida por el cliente.
- Cada commit ha de dejar producto funcional.
- Cada tarea ha de estar asignada a alguien, tener un a estimación en tiempo, y un estado de completitud.
- Ha de estar publicado para poder ver una versión live, y el enlace ha de estar en el `README.md`


## Descripción de las funcionalidades a realizar:

A partir de las 'Movies' del API: https://developer.themoviedb.org/docs/getting-started

Proponer una solución que permita:
 - 3 títulos 'trending' (en grande) -> poster + título + descripción + link detalle
 - N títulos por 'genres' (3 géneros a elegir) más pequeños -> poster + título + link detalle


## Bolas extra

### Búsqueda de películas
  Incluir una página de búsqueda, para que los usuarios puedan buscar por títulos.



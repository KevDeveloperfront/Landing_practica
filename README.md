# Landing_practica

## 🛠️ Tecnologías Utilizadas
 - Frontend: HTML5, CSS3 (pueden usarse preprocesadores como SASS opcionalmente)

 - Control de Versiones: Git con GitHub

 - Metodología: Git Flow simplificado

## 📋 Flujo de Trabajo en Git/GitHub
    1. Estructura de Ramas:
       * main → Versiones estables (protegida)
       * develop → Integración de features (protegida)
       * feature/* → Desarrollo de nuevas funcionalidades

    2. Nomenclatura de Ramas:
       * feature/nombre-breve-descripcion
            Ejemplos:
                - feature/header-navigation
                - feature/contact-form
                - feature/footer-redesign

    3. Convención de Commits Formato:
        text  [tipo]: descripción breve
              [descripción extendida opcional]

    Tipos aceptados:
        feat: Nueva funcionalidad
        fix: Corrección de errores
        style: Cambios en estilos (CSS)
        refactor: Mejoras de código sin funcionalidad nueva
        docs: Documentación

## Ejemplos:

text feat: 
    - add responsive navigation menu
    - Implement mobile-first responsive design
    - Add hamburger menu for mobile devices

## 1. Proceso de Pull Requests
    Crear PR desde feature/* hacia develop
    Título del PR: [TIPO] Descripción breve
    Ej: [FEAT] Navigation menu

# ep2-ms-vehiculos
## 1. Convención de Commits

- Durante el desarrollo del proyecto se utilizó una convención formal
como Conventional Commits, principalmente Fix/Fixed y Feat/Feature.

- Los mensajes de commit se utilizaron para describir de manera breve
los cambios realizados en cada modificación del proyecto.

## 2. Ramas y Flujo de Trabajo

- Utilizamos Trunk-Based Development, trabajando principalmente sobre
la rama `main`.
- Se creó un Dockerfile para contenerizar el microservicio

## 3. Integración Continua y Revisión

- **GitHub Actions:** Cada vez que hacemos `git push`, se activa automáticamente el pipeline de CI para verificar que el proyecto siga compilando.
                      
- **Github Secrets:** Se agregó la IP, db username y db password como secretos de github para no dejarlos publicos

## 4. Declaración de asistencia con IA

- Se utilizaron herramientas de IA para la estructuracion de la documentacion del proyecto.

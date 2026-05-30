# 🛡️ OverTheWire Bandit: Security Labs (0-33)
**Autor:** Franco Campos
**Rol:** Analista de Ciberseguridad | Estudiante de Ingeniería de Arquitectura Cloud##
**Ubicación:** Mendoza, Argentina##
## 📝 Resumen del Proyecto
Este repositorio contiene la documentación técnica y el análisis de la resolución del laboratorio Bandit (OverTheWire). Este desafío está diseñado para certificar competencias avanzadas en el manejo de la terminal Linux, fundamentales para la Arquitectura Cloud y la Ciberseguridad.
## 🚀 Habilidades Técnicas Consolidadas
- **Linux Fundamentals:** Navegación profunda, filtros complejos (grep, uniq, sort) y manipulación de flujos de datos.
- **IAM & Seguridad de Acceso:** Gestión de identidades, permisos de archivos (chmod) y manejo de llaves privadas SSH.
- **Análisis Forense en Git:** Recuperación de secretos en historial de commits, ramas y etiquetas (Tags).
- **Networking & Protocolos:** Interacción con servicios de red mediante nmap, netcat y comunicación cifrada con openssl (SSL/TLS).
- **Automatización:** Análisis y explotación de tareas programadas (Cron Jobs) y desarrollo de scripts en Bash.
## 🛠️ Fases del Laboratorio
### Fase 1: Análisis y Filtrado de Datos
Aprendizaje de herramientas para localizar información sensible entre miles de archivos.
- **Comandos clave:** find, cat, strings, base64.
### Fase 2: Identidad y SSH (Identity Management)
Gestión de credenciales para el acceso a servidores remotos.
- **Dato destacado:** En el nivel 14, apliqué el principio de propiedad (Ownership) para configurar correctamente permisos chmod 600 sobre llaves privadas RSA.
### Fase 3: Seguridad en Control de Versiones (Git)
Auditoría de repositorios para detectar la fuga de secretos (Secret Leaks).
- **Herramientas:** git log, git checkout, git tag.
## 🔍 Caso Destacado: Escalada de Privilegios (Nivel 19)
Durante el laboratorio, identifiqué y exploté un binario con el bit SUID activo, permitiendo ejecutar procesos con los privilegios de un usuario superior para acceder a credenciales restringidas.
## 🏁 Conclusión Personal
Completar este laboratorio de 33 niveles a los 31 años es una prueba de mi capacidad de resiliencia y resolución de problemas. La lógica aplicada aquí (investigación de documentación, scripting y persistencia) es la misma que aplico hoy en mis estudios de Ingeniería Cloud.
[Mi Perfil de LinkedIn](https://www.linkedin.com/in/francocampos/) | [Mi Portafolio de GitHub](https://github.com/FrancoCampos231)

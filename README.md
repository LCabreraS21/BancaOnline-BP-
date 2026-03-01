Este repositorio contiene el documento técnico en formato PDF que describe la arquitectura propuesta para el sistema de banca por internet de la entidad BP. El diseño se basa en el modelo C4 e incluye los diagramas de Contexto, Contenedores y Componentes, junto con justificaciones detalladas de cada decisión arquitectónica.

📌 Descripción del Proyecto
El sistema permite a los usuarios:

Consultar el histórico de movimientos.

Realizar transferencias entre cuentas propias e interbancarias.

Recibir notificaciones sobre cada transacción realizada.

La arquitectura considera:

Integración con sistemas Core y complementarios.

Autenticación segura mediante OAuth2.0 (Authorization Code + PKCE).

Onboarding biométrico con reconocimiento facial.

Persistencia de datos para clientes frecuentes.

Alta disponibilidad, tolerancia a fallos y monitoreo continuo.

🧠 Enfoque Arquitectónico
Diseñado bajo el modelo C4, el documento incluye:

Diagrama de Contexto: visión general para usuarios no técnicos.

Diagrama de Contenedores: estructura técnica de aplicaciones, servicios y bases de datos.

Diagrama de Componentes: detalle técnico de microservicios, patrones y protocolos.

🛠️ Tecnologías y Patrones
Frontend: SPA (Angular/React), App móvil (Flutter/React Native).

Backend: Microservicios desacoplados con API Gateway.

Seguridad: OAuth2.0 + PKCE, MFA, biometría.

Persistencia: CQRS + Repository.

Infraestructura: Azure, Kubernetes, Service Mesh.

Notificaciones: Publisher/Subscriber con fan-out hacia SMS, Email y Push.

📄 Contenido del Repositorio
Arquitectura de Solución BP.pdf: Documento técnico con diagramas y explicaciones.

Diagramas generados en formato imagen.

Este archivo README.md.

👨‍💻 Autor
Luis Miguel Cabrera Soledispa  
Guayaquil, Ecuador

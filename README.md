# Diagrama del Flujo de la Aplicación

```mermaid
flowchart TD
    A[Inicio] --> B[Recibir solicitud]
    B --> C{¿Datos válidos?}
    C -- Sí --> D[Procesar solicitud]
    C -- No --> E[Mostrar error]
    D --> F[Enviar respuesta]
    E --> F
    F --> G[Fin]

[![project](https://github.com/user-attachments/assets/78cb93c5-a069-4fb2-b43e-568ef815806b)](https://copytesla.netlify.app/)!

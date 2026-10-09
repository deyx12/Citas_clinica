# Portal de citas — Clínica Belén

Portal web para el registro de pacientes y la gestión de citas médicas. Fue desarrollado con Next.js, React y una base de datos PostgreSQL en Supabase.

## Iniciar el proyecto

Se requiere Node.js 24 y configurar la conexión con Supabase en el archivo `.env`.

```bash
npm install
npm run dev
```

Después, abra `http://localhost:3000`.

El paciente debe registrarse con su documento y contraseña. Luego puede seleccionar la especialidad, el profesional, el día y la hora de la cita.

## Funcionalidades principales

- Registro e inicio de sesión de pacientes.
- Selección de especialidad y profesional.
- Consulta de horarios disponibles.
- Agendamiento de citas.
- Consulta de citas registradas.
- Reprogramación y cancelación de citas.
- Confirmación de asistencia.
- Protección para evitar reservas duplicadas.
- Diseño adaptable para computadores y celulares.

## Base de datos

La información de pacientes, sesiones y citas se almacena en PostgreSQL mediante Supabase.

Las contraseñas se almacenan de forma segura y la conexión con la base de datos se realiza desde el servidor.

## Limitaciones actuales

Los profesionales y horarios utilizados son datos de demostración. El sistema tampoco incluye recuperación de contraseña, envío de correos o mensajes SMS ni administración de agendas por parte del personal de la clínica.

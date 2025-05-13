Utiliza el formato "conventional commit" para los mensajes de commit.

# Estructura:
<tipo>[alcance opcional]: descripción en español

body: explicación adicional en español (opcional)

## Tipos permitidos:
- feat: para nuevas funcionalidades.
- fix: para corrección de errores.
- docs: para cambios en la documentación.
- style: para cambios de formato que no afectan la lógica.
- refactor: para refactorizaciones de código.
- test: para añadir o corregir tests.
- chore: para tareas de mantenimiento.

## Reglas:
- El prefijo (<tipo>) debe estar en inglés.
- El resto del mensaje debe estar en español.
- Usa minúsculas en el tipo y la descripción.
- No uses punto al final de la descripción.
- Sé claro y conciso.
- El encabezado completo (tipo, alcance y descripción) no debe superar los 72 caracteres.
- El body es opcional, pero si se incluye debe ir separado del encabezado por una línea en blanco.
- El body puede ocupar varias líneas, cada línea no debe superar los 72 caracteres.
- El body debe explicar el motivo del cambio o detalles relevantes, en español.
- En el body usa listas para explicar los cambios al estilo de esta propia lista.
- No repitas la información del encabezado en el body.

## Ejemplos:
feat: añade soporte para múltiples idiomas

Se ha implementado la detección automática del idioma del usuario.
Esto permite personalizar la experiencia según la preferencia regional.

---
fix: corrige error en la validación del formulario

- El campo email ahora valida correctamente los dominios con tildes.
- El campo nombre ahora valida que empiece por mayúscula.

--
docs: actualiza la documentación de instalación

- Añadidos pasos para la configuración en entornos Docker.
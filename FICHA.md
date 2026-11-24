# Ficha de mi aplicación · Hito 0

- **Alumno/a:** Jaime González Peregrín
- **Temática:** gestión de una clínica de fisioterapia (ClinPlates)
- **Qué gestiona:** citas

## Campos

Al menos 7. Como mínimo: 2 de texto · 1 número entero · 1 número decimal · 1 opción de una lista · 1 opción entre 2 o 3 · 1 sí/no.

| # | Campo | Tipo de dato | Componente | Ejemplo de valor / opciones |
|---|-------|--------------|------------|-----------------------------|
| 1 | Paciente | texto | campo de texto | Carmen Díaz |
| 2 | Motivo | texto | campo de texto | Dolor lumbar |
| 3 | Fecha | texto | campo de texto | 19/11/2026 |
| 4 | Hora | texto | campo de texto | 13:30 |
| 5 | Duración (min) | entero | selector numérico | 30 |
| 6 | Precio (€) | decimal | campo de texto | 45,50 |
| 7 | Tratamiento | lista | lista desplegable | Revisión / Limpieza / Primera visita / Presupuesto |
| 8 | Modalidad | opción | botones de opción | Presencial / Online |
| 9 | Confirmada | sí/no | casilla | Sí |

Tipos de dato: `texto`, `entero`, `decimal`, `lista`, `opción`, `sí/no`.
Componentes: `campo de texto`, `selector numérico`, `lista desplegable`, `botones de opción`, `casilla`.

## Pantallas

Las fotos de tus bocetos, en la carpeta `bocetos/` con estos nombres (`.jpg` o `.png`):

| Pantalla | Foto |
|----------|------|
| Inicio de sesión | `bocetos/1_inicio_sesion.jpg` |
| Ventana principal | `bocetos/2_ventana_principal.jpg` |
| Formulario de alta | `bocetos/3_formulario.jpg` |

### Ventana principal

- **Menús y sus opciones:**
  - Archivo: Cerrar sesión, Salir
  - Citas: Nueva cita, Editar cita, Borrar cita
  - Ayuda: Acerca de
- **Columnas de la tabla:** Hora, Paciente, Tratamiento, Duración (min), Precio (€), Modalidad, Confirmada

### Qué hace cada botón

- **Entrar** (inicio de sesión): comprueba usuario y contraseña y abre la ventana principal.
- **+ Nueva cita**: abre el formulario de alta vacío.
- **✎ (editar)**: abre el formulario con los datos de esa cita para modificarlos.
- **✕ (borrar)**: pide confirmación y borra la cita de la tabla.
- **Guardar** (formulario): comprueba los campos, guarda la cita, cierra el formulario y la muestra en la tabla.
- **Cancelar / X** (formulario): cierra el formulario sin guardar.

### Mensajes

- Si el usuario o la contraseña están mal: «Usuario o contraseña incorrectos.»
- Si falta un campo obligatorio en el formulario: «Rellena todos los campos obligatorios.»

# parcial1-Nilsson-Garcia
# TechServ – Catálogo de Servicios Digitales

Proyecto desarrollado para el **Parcial 1 – Programación Web**.

> [!NOTE]
> Tecnologías utilizadas
- HTML5
- CSS3 (Variables CSS, Flexbox, Grid)
- JavaScript (ES6+, RegEx)
- Bootstrap 5.3
- Bootstrap Icons 1.11

##  implementacion

### 1. Catálogo de servicios
- 8 servicios digitales organizados en cards con Bootstrap grid responsive.
- Cada card incluye: ícono, nombre, descripción y botón "Solicitar servicio".

### 2. Interacción con servicios
- Al hacer clic en "Solicitar servicio" se incrementa el contador global.
- Se muestra un **modal de Bootstrap** con el mensaje: *"Servicios seleccionados: X"*.
- El contador también aparece en la navbar y en un botón flotante en pantalla.

### 3. Formulario de registro de cliente
Campos con validación mediante **expresiones regulares (RegEx)**:
| Campo | Validación |
|---|---|
| Nombre | Solo letras y espacios, mín. 2 caracteres |
| Apellidos | Solo letras y espacios, mín. 2 caracteres |
| Edad | Número entre 1 y 120 |
| Ciudad | Solo letras, mín. 2 caracteres |
| Teléfono | Exactamente 10 dígitos |
| Correo | Formato `usuario@dominio.ext` |
| Servicio | Selección obligatoria |

Al presionar "Registrar" aparece un **modal** mostrando todos los datos ingresados.

### 4. Modo oscuro / claro
- Botón en la navbar alterna entre modo claro y oscuro.
- El texto del botón cambia: *"Modo oscuro"* ↔ *"Modo claro"*.
- Transición suave mediante variables CSS.

##  Estructura del proyecto

```
parcial1-Nilsson-Garcia/
├── index.html
├── README.md
├── gitignore
├── script.js
└── style.css
```

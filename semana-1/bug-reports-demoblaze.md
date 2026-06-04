# Bug Reports — demoblaze.com

**Tester:** Juan Esteban Rivera   
**Fecha:** Junio 2026  
**Entorno:** demoblaze.com | Chrome 124.0 | Windows 11  

---

## BUG-001 — Campo Username no valida formato ni longitud mínima

| Campo | Detalle |
|---|---|
| **ID** | BUG-001 |
| **Fecha** | 2026-06-04 |
| **Severidad** | Medium |
| **Prioridad** | Low |
| **Estado** | Abierto |

### Descripción
El formulario de registro permite crear una cuenta ingresando cualquier texto en el campo Username, sin validar formato ni longitud mínima.

### Pasos para reproducir
1. Abrir https://demoblaze.com
2. Hacer clic en **Sign up**
3. Ingresar un username de 1 carácter (ej: `a`)
4. Ingresar cualquier contraseña
5. Hacer clic en **Sign up**

### Resultado esperado
El sistema valida el formato del username y muestra un mensaje de error si no cumple los requisitos mínimos definidos.

### Resultado actual
El registro se completa exitosamente con cualquier texto, sin ningún mensaje de validación.

### Evidencia
> <img width="1898" height="906" alt="image" src="https://github.com/user-attachments/assets/dadc0a58-08fa-44fd-9ddd-864bc7efda1e" />
> <img width="1877" height="196" alt="image" src="https://github.com/user-attachments/assets/cef72929-8dbf-40ef-a876-8fc10f93e7dc" />


---

## BUG-002 — Formulario "Place Order" no valida longitud mínima de los campos

| Campo | Detalle |
|---|---|
| **ID** | BUG-002 |
| **Fecha** | 2026-06-04 |
| **Severidad** | High |
| **Prioridad** | High |
| **Estado** | Abierto |

### Descripción
El formulario de compra "Place Order" permite completar una transacción ingresando un solo carácter en cada campo, sin ningún tipo de validación de datos.

### Pasos para reproducir
1. Abrir https://demoblaze.com
2. Iniciar sesión con una cuenta existente
3. Agregar cualquier producto al carrito
4. Hacer clic en **Cart**
5. Hacer clic en **Place Order**
6. Ingresar un solo carácter en cada campo del formulario (nombre, tarjeta, mes, año, etc.)
7. Hacer clic en **Purchase**

### Resultado esperado
El sistema valida los campos del formulario y muestra un mensaje de error si los datos ingresados no cumplen el formato o longitud mínima requeridos.

### Resultado actual
La compra se procesa exitosamente mostrando el mensaje "Thank you for your purchase" sin ninguna validación de los datos ingresados.

### Evidencia
> <img width="1872" height="897" alt="image" src="https://github.com/user-attachments/assets/3e0145ac-a81e-4d65-841a-8bf7a3e65886" />
> <img width="1858" height="882" alt="image" src="https://github.com/user-attachments/assets/f806cc35-9bd5-4fde-9ac0-983064f2d6f4" />


---

*Reporte generado como parte del portafolio de práctica QA — Semana 1*

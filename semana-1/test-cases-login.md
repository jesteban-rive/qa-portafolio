# Test Cases — Login | demoblaze.com

**Tester:** Tu nombre  
**Fecha:** Junio 2026  
**Módulo:** Autenticación — Login  
**Entorno:** demoblaze.com | Chrome | Windows  
**Total de casos:** 5  
**Resultados:** ✅ 5 PASS — ❌ 0 FAIL

---

## Resumen de ejecución

| ID | Título | Estado |
|---|---|---|
| TC-001 | Login exitoso con credenciales válidas | ✅ PASS |
| TC-002 | Login con contraseña incorrecta | ✅ PASS |
| TC-003 | Login con usuario inexistente | ✅ PASS |
| TC-004 | Login con campos vacíos | ✅ PASS |
| TC-005 | Login con espacios en blanco | ✅ PASS |

---

## TC-001 — Login exitoso con credenciales válidas

| Campo | Descripción |
|---|---|
| **ID** | TC-001 |
| **Título** | Verificar inicio de sesión con credenciales válidas |
| **Precondición** | Usuario registrado en Demoblaze |
| **Entorno** | demoblaze.com | Chrome | Windows |

### Pasos
1. Ingresar a https://demoblaze.com
2. Hacer clic en **Log in**
3. Ingresar usuario válido
4. Ingresar contraseña válida
5. Hacer clic en **Log in**

### Resultados
| | Descripción |
|---|---|
| **Esperado** | El usuario inicia sesión correctamente y su nombre aparece en la barra de navegación superior. |
| **Actual** | El usuario inicia sesión correctamente y su nombre aparece en la barra de navegación superior. |
| **Estado** | ✅ PASS |

---

## TC-002 — Login con contraseña incorrecta

| Campo | Descripción |
|---|---|
| **ID** | TC-002 |
| **Título** | Verificar inicio de sesión con contraseña incorrecta |
| **Precondición** | Usuario registrado en Demoblaze |
| **Entorno** | demoblaze.com | Chrome | Windows |

### Pasos
1. Ingresar a https://demoblaze.com
2. Hacer clic en **Log in**
3. Ingresar un usuario válido
4. Ingresar una contraseña incorrecta
5. Hacer clic en **Log in**

### Resultados
| | Descripción |
|---|---|
| **Esperado** | El sistema muestra un mensaje de error indicando credenciales incorrectas y deniega el acceso. |
| **Actual** | El sistema muestra la alerta: *"Wrong password."* y el acceso es denegado. |
| **Estado** | ✅ PASS |

---

## TC-003 — Login con usuario inexistente

| Campo | Descripción |
|---|---|
| **ID** | TC-003 |
| **Título** | Verificar inicio de sesión con usuario inexistente |
| **Precondición** | Ninguna |
| **Entorno** | demoblaze.com | Chrome | Windows |

### Pasos
1. Ingresar a https://demoblaze.com
2. Hacer clic en **Log in**
3. Ingresar un usuario que no exista en el sistema
4. Ingresar cualquier contraseña
5. Hacer clic en **Log in**

### Resultados
| | Descripción |
|---|---|
| **Esperado** | El sistema muestra un mensaje indicando que el usuario no existe y deniega el acceso. |
| **Actual** | El sistema muestra la alerta: *"User does not exist."* y el acceso es denegado. |
| **Estado** | ✅ PASS |

---

## TC-004 — Login con campos vacíos

| Campo | Descripción |
|---|---|
| **ID** | TC-004 |
| **Título** | Verificar inicio de sesión con usuario y contraseña vacíos |
| **Precondición** | Ninguna |
| **Entorno** | demoblaze.com | Chrome | Windows |

### Pasos
1. Ingresar a https://demoblaze.com
2. Hacer clic en **Log in**
3. Dejar los campos de usuario y contraseña vacíos
4. Hacer clic en **Log in**

### Resultados
| | Descripción |
|---|---|
| **Esperado** | El sistema muestra un mensaje indicando que los campos son obligatorios y deniega el acceso. |
| **Actual** | El sistema muestra la alerta: *"Please fill out Username and Password."* y deniega el acceso. |
| **Estado** | ✅ PASS |

---

## TC-005 — Login con espacios en blanco

| Campo | Descripción |
|---|---|
| **ID** | TC-005 |
| **Título** | Verificar inicio de sesión utilizando espacios en blanco en los campos |
| **Precondición** | Ninguna |
| **Entorno** | demoblaze.com | Chrome | Windows |

### Pasos
1. Ingresar a https://demoblaze.com
2. Hacer clic en **Log in**
3. Ingresar únicamente espacios en blanco en usuario y contraseña
4. Hacer clic en **Log in**

### Resultados
| | Descripción |
|---|---|
| **Esperado** | El sistema trata los espacios como campos vacíos y no permite el acceso. |
| **Actual** | El sistema muestra la alerta: *"Please fill out Username and Password."* y deniega el acceso, tratando los espacios como campos vacíos. |
| **Estado** | ✅ PASS |

---

*Test cases generados como parte del portafolio de práctica QA — Semana 1*

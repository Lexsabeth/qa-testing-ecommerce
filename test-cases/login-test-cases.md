# Casos de Prueba - Login Ecommerce

## TC01 - Login exitoso

Precondición  
El usuario debe estar registrado.

Pasos

1. Abrir la página de login
2. Ingresar email válido
3. Ingresar contraseña válida
4. Presionar botón "Ingresar"

Resultado esperado

El usuario accede correctamente a su cuenta.

---

## TC02 - Login con contraseña incorrecta

Pasos

1. Abrir la página de login
2. Ingresar email válido
3. Ingresar contraseña incorrecta
4. Presionar ingresar

Resultado esperado

El sistema muestra mensaje:

"Usuario o contraseña incorrectos".

---

## TC03 - Campos obligatorios vacíos

Pasos

1. Ir a login
2. Dejar campos vacíos
3. Presionar ingresar

Resultado esperado

El sistema muestra validación de campos obligatorios.

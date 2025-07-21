# 🧪 Prueba Técnica: Desarrollo de un Sistema de Login y Visualización de Datos

**📅 Fecha límite de entrega:** 22 de julio de 2025 máximo 23:59 hrs.  
**🎯 Objetivo:** Diseñar e implementar una aplicación web donde el usuario deba iniciar sesión y, según su rol, se muestre la información correspondiente.

---

Usa el archivo `usuarios.json` para obtener los datos de los usuarios. Puedes añadir más usuarios si lo deseas, siempre y cuando siga la misma estructura.

## 🔐 Reglas de Visualización por Rol

La visibilidad de los datos en la aplicación depende del rol del usuario autenticado. A continuación se detallan las reglas:

- **Admin**
  - [ ] ✅ Puede ver los datos de **todos los usuarios**.
  - [ ] Incluye: otros administradores, supervisores y usuarios.

- **Supervisor**
  - [ ] ✅ Puede ver los datos de **supervisores** y **usuarios**.
  - [ ] ❌ **No puede ver** los datos de usuarios con rol **admin**.

- **Usuario**
  - [ ] ✅ Solo puede ver **sus propios datos**.
  - [ ] ❌ No puede ver a otros usuarios, sin importar su rol.

---

## ✅ Requisitos

### 1. Funcionalidad

- [ ] Sistema de login con autenticación básica (usuario y contraseña).
- [ ] Gestión de sesiones (el usuario debe permanecer autenticado mientras navega).
- [ ] Roles de usuario al menos de tres tipos: `admin`, `usuario` y `supervisor`.
- [ ] Visualización de datos en una tabla cargada desde el archivo JSON.
- [ ] El contenido de la tabla debe variar según el rol.
- [ ] Logout funcional.

---

### 2. Requisitos Técnicos

- [ ] Debes utilizar obligatoriamente el stack tecnológico (recomendado: HTML/CSS/JavaScript/JQuery + backend en Python Litestar).
- [ ] El frontend debe ser claro y funcional (no se requiere diseño avanzado).
- [ ] El backend debe validar credenciales y manejar sesiones.
- [ ] Código bien estructurado y comentado.
- [ ] No se permite el uso de frameworks de autenticación externos (como Firebase Auth o Auth0).

---

### 3. Extras (Opcionales)

- [ ] Uso de DataTables o similar para la visualización de datos.
- [ ] Implementación de hashing de contraseñas.
- [ ] Uso de base de datos (SQLite, MySQL, MongoDB, etc.).
- [ ] Pruebas unitarias básicas.
- [ ] Despliegue en un servidor gratuito (ej. Render, Vercel, Netlify, etc.).

---

### 4. Entregables

- [ ] Código fuente en un repositorio (GitHub, GitLab, etc.).
- [ ] Instrucciones claras para ejecutar el proyecto localmente (`README.md`).

---

### 5. Criterios de Evaluación

- [ ] Cumplimiento de los requisitos funcionales.
- [ ] Claridad y organización del código.
- [ ] Seguridad básica implementada.
- [ ] Buenas prácticas de desarrollo.
- [ ] Creatividad y valor agregado (si aplica).

---

## Referencias

- [ ] Documentación de Framework Litestar: https://litestar.dev/

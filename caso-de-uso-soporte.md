# Caso de Uso: Problema de Acceso al Sistema

## Actor
Usuario

## Problema
El usuario no puede iniciar sesión en el sistema debido a que olvidó su contraseña o la cuenta fue bloqueada por múltiples intentos fallidos.

## Flujo Principal
1. El usuario contacta al departamento de soporte.
2. El agente de soporte valida la identidad del usuario.
3. El agente genera un restablecimiento de contraseña.
4. El sistema envía un enlace de recuperación al correo del usuario.
5. El usuario restablece la contraseña.
6. El usuario accede correctamente al sistema.

## Flujo Alterno
**A1: El usuario no recuerda su correo registrado**
1. El agente solicita datos adicionales de verificación.
2. Se valida la información con el área administrativa.
3. Se actualiza el correo del usuario.
4. Se envía el enlace de recuperación al nuevo correo.

**A2: Cuenta bloqueada**
1. El sistema bloquea la cuenta tras varios intentos fallidos.
2. El usuario contacta soporte.
3. El agente desbloquea la cuenta manualmente.
4. El usuario intenta iniciar sesión nuevamente.

## Resultado
El usuario recupera el acceso al sistema de manera segura y satisfactoria.

## Observaciones
Este proceso reduce incidencias repetitivas y mejora la experiencia del usuario.


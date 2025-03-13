# Guía de Restablecimiento de Fábrica para Lenovo 🔄

## Introducción
Esta guía te ayudará a realizar un restablecimiento de fábrica en tu laptop Lenovo. Sigue la lista de verificación para cada método y selecciona la opción que mejor se adapte a tu situación.

## Antes de Comenzar ⚠️

- [ ] Respalda todos tus archivos y documentos importantes
- [ ] Anota todas las contraseñas necesarias
- [ ] Mantén el cargador de tu laptop conectado durante el proceso
- [ ] Reserva al menos 1-2 horas para el proceso de restablecimiento

---

## Opción 1: Restablecer desde el Entorno de Recuperación de Windows 💻

### Acceso al Menú de Recuperación
- [ ] Reinicia tu laptop
- [ ] Fuerza 3 apagados durante el inicio (mantén presionado el botón de encendido hasta que se apague)
- [ ] En el tercer reinicio, entrarás en **Reparación Automática** (**Automatic Repair**)
- [ ] Selecciona **Opciones Avanzadas** (**Advanced Options**)

### Proceso de Restablecimiento
- [ ] Navega a **Solucionar problemas** (**Troubleshoot**) ➡️ **Restablecer este PC** (**Reset This PC**) ➡️ **Quitar todo** (**Remove Everything**)
- [ ] Cuando se te pregunte sobre la limpieza de la unidad, selecciona **Limpiar la unidad completamente** (**Clean the drive fully**) (más seguro pero toma más tiempo)
- [ ] Sigue las instrucciones en pantalla para completar el restablecimiento
- [ ] Windows se reinstalará desde la partición de recuperación de Lenovo (si está disponible)

### Verificación de Éxito
- [ ] El sistema reinicia a la configuración de Windows
- [ ] La instalación de Windows se completa exitosamente
- [ ] Puedes iniciar sesión en un sistema nuevo

---

## Opción 2: Usar la Recuperación OneKey de Lenovo 🔑

### Acceso a la Herramienta de Recuperación de Lenovo
- [ ] Apaga completamente tu laptop
- [ ] Enciéndela y presiona repetidamente la tecla **F11**
- [ ] Alternativamente, presiona el **Botón Novo** (botón pequeño cerca del puerto de carga en algunos modelos)

### Proceso de Restablecimiento
- [ ] En el **Menú del Botón Novo**, selecciona **Recuperación del Sistema** (**System Recovery**)
- [ ] Sigue las instrucciones para restaurar el sistema a la configuración de fábrica
- [ ] Espera a que el proceso se complete (puede tomar 30-60 minutos)

### Verificación de Éxito
- [ ] El sistema reinicia automáticamente
- [ ] Aparece la pantalla de configuración de Lenovo
- [ ] La instalación de Windows se completa con el software de Lenovo preinstalado

---

## Opción 3: Instalación Limpia de Windows 🔧
*Usa este método si las Opciones 1 y 2 fallan*

### Requisitos
- [ ] Acceso a otra computadora
- [ ] Unidad USB (8GB o más grande)
- [ ] Conexión a Internet para descargar la Herramienta de Creación de Medios de Windows

### Crear Medio de Instalación
- [ ] En otra computadora, descarga la **Herramienta de Creación de Medios** desde el sitio oficial de Microsoft
- [ ] Ejecuta la herramienta y selecciona **Crear medios de instalación**
- [ ] Sigue las indicaciones para crear una unidad USB de arranque

### Proceso de Instalación
- [ ] Conecta la unidad USB a tu laptop Lenovo
- [ ] Reinicia y presiona **F12** para acceder al menú de arranque
- [ ] Selecciona la unidad USB desde el menú de arranque
- [ ] Cuando cargue el instalador de Windows, selecciona **Instalación Personalizada** (**Custom Install**)
- [ ] Elimina todas las particiones existentes (⚠️ ¡Esto borrará TODOS los datos!)
- [ ] Crea una nueva partición y continúa con la instalación

### Post-Instalación
- [ ] Completa la configuración de Windows
- [ ] Descarga e instala los controladores de Lenovo desde el sitio web de Soporte de Lenovo
- [ ] Instala el software esencial

---

## Consejos de Solución de Problemas 🛠️

### Si el Restablecimiento Falla
- [ ] Prueba una opción de restablecimiento diferente de esta guía
- [ ] Verifica si hay problemas de hardware (particularmente con el disco duro)
- [ ] Considera conectar la unidad a otra computadora para recuperar archivos importantes

### Información de Licencia
- [ ] Las laptops Lenovo generalmente tienen la licencia de Windows integrada en la BIOS
- [ ] No deberías necesitar ingresar manualmente una clave de producto
- [ ] Si se te solicita, selecciona "No tengo una clave de producto" y Windows debería activarse automáticamente

### Instalación de Controladores
- [ ] Visita el [sitio web de Soporte de Lenovo](https://support.lenovo.com)
- [ ] Ingresa el número de modelo de tu laptop o usa la detección automática
- [ ] Descarga e instala los controladores en este orden:
  - Controladores del chipset
  - Controladores de pantalla
  - Controladores de red
  - Controladores de audio
  - Otros controladores de dispositivos

---

## Lista de Verificación Final ✅

- [ ] Windows está instalado exitosamente
- [ ] Todo el hardware funciona correctamente
- [ ] Las conexiones de red funcionan
- [ ] Windows está activado
- [ ] Los controladores esenciales están instalados
- [ ] El sistema está actualizado con las últimas actualizaciones de Windows

---

*Si encuentras problemas persistentes después de intentar todos los métodos, considera consultar con un especialista de soporte técnico de Lenovo o visitar un centro de servicio autorizado.*

# Taller de Aplicaciones Móviles - Semana 6

Este proyecto corresponde al desarrollo de una aplicación Android que permite el **inicio de sesión de usuarios** y el **almacenamiento de su ubicación GPS en Firebase Realtime Database**.  

Se desarrolla como parte del taller de aplicaciones móviles, aplicando control de versiones con GitHub y trabajo colaborativo.

---

## 📌 Requerimientos Funcionales

1. El sistema debe permitir que el usuario inicie sesión con credenciales válidas.
2. Si el login es exitoso, la aplicación debe obtener la ubicación GPS del dispositivo.
3. La aplicación debe almacenar la ubicación del usuario en **Firebase Realtime Database**, bajo un nodo asociado al usuario.
4. El sistema debe mostrar en pantalla (TextView) la latitud y longitud actuales del dispositivo.
5. La aplicación debe solicitar permisos de ubicación al usuario en tiempo de ejecución.
6. El sistema debe actualizar la ubicación cada vez que cambie la posición del dispositivo.

---

## ⚙️ Requerimientos No Funcionales

1. **Disponibilidad:** La aplicación debe funcionar en dispositivos con Android 8.0 (Oreo) o superior.  
2. **Usabilidad:** La interfaz debe ser sencilla y clara, mostrando la ubicación en un campo de texto.  
3. **Seguridad:** La app debe validar permisos de ubicación antes de acceder al GPS.  
4. **Escalabilidad:** El sistema debe permitir agregar más funcionalidades sobre Firebase (ej. autenticación real con FirebaseAuth).  
5. **Mantenibilidad:** El código debe estar organizado en clases separadas para facilitar futuras modificaciones.  
6. **Colaboración:** El proyecto debe mantenerse en un repositorio de GitHub con control de versiones y ramas para cada historia de usuario.  

---

## 🚀 Instalación y Configuración

1. Clonar este repositorio:
   ```bash
   git clone https://github.com/Lcastrou362/TALLER-DE-APLICACIONES-M-VILES-SEMANA6.git

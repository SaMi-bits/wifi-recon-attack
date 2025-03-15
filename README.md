# 🔥 Análisis y Reconocimiento de Redes WiFi con Kali Linux y Wifislax

Este proyecto documenta un proceso detallado de reconocimiento, análisis y explotación de vulnerabilidades en redes WiFi 
utilizando herramientas avanzadas de Kali Linux y Wifislax.

> ⚠️ **Nota Importante:** Este proyecto es **estrictamente educativo** y está orientado a aprender sobre ciberseguridad y prácticas éticas de pruebas de penetración.
> No se aprueba ni se fomenta ningún uso no autorizado o ilegal de la información aquí presentada.

---

## 🛠️ Herramientas Utilizadas

| Herramienta  | Descripción |
|-------------|------------|
| **`aircrack-ng`**  | Suite para auditoría de redes WiFi y ataques de desautenticación. |
| **`bettercap`**  | Herramienta avanzada para escaneo, manipulación y análisis de redes. |
| **`hydra`**  | Realización de ataques de fuerza bruta sobre formularios de inicio de sesión. |
| **`reaver`**  | Explotación de vulnerabilidades en redes con WPS habilitado. |
| **`burpsuite`**  | Análisis y manipulación de tráfico HTTP/S. |
| **`nmap`**  | Escaneo de puertos y reconocimiento de hosts activos. |
| **`slapt-get`**  | Gestor de paquetes en Wifislax para instalación de herramientas adicionales. |

---

## ⚙️ Requisitos Previos

1. **Kali Linux o Wifislax** instalado en tu máquina o en un entorno virtual.
2. **Tarjeta WiFi compatible** con modo monitor (ej. TP-Link TL-WN722N).
3. **Acceso a la terminal** con privilegios de `sudo`.
4. **Conexión estable** para la descarga de herramientas.

---

## 🚀 Proceso de Reconocimiento y Análisis

### 1️⃣ **Configuración del Entorno**
```bash
sudo apt update && sudo apt upgrade
sudo apt install aircrack-ng bettercap hydra reaver burpsuite -y

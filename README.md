Conversor de Monedas en Java

Un conversor de monedas avanzado desarrollado en Java que utiliza la API de ExchangeRate-API para obtener tasas de cambio en tiempo real.

 Características

- ✅ **Conversión en tiempo real** usando ExchangeRate-API
- ✅ **Soporte para 15+ monedas** diferentes
- ✅ **Historial de conversiones** con marca de tiempo
- ✅ **Interfaz de línea de comandos** fácil de usar
- ✅ **Manejo de errores** robusto
- ✅ **Código abierto** y fácil de extender

 Tecnologías Utilizadas

- **Java 11+**
- **GSON** - Para análisis de JSON
- **HttpClient** - Para solicitudes HTTP
- **ExchangeRate-API** - Para tasas de cambio

 Instalación

### Prerrequisitos
- Java JDK 11 o superior
- Biblioteca GSON (gson-2.10.1.jar)

### Pasos de instalación

1. **Clonar o descargar** el proyecto
2. **Colocar gson-2.10.1.jar** en la carpeta `lib/`
3. **Compilar** el proyecto:
   ```bash
   javac -cp "lib/gson-2.10.1.jar" src/ConversorMonedas.java

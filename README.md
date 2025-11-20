# Proyecto Compostera Escolar 🌱

Una aplicación móvil Android para gestionar y monitorear composteras escolares, promoviendo la educación ambiental y el compostaje como práctica sostenible.

## 📋 Descripción

Proyecto Compostera Escolar es una aplicación educativa que permite a estudiantes y profesores monitorear el proceso de compostaje, registrar datos importantes como temperatura y humedad del suelo, y aprender sobre prácticas de sostenibilidad ambiental.

## ✨ Características

- **Conexión Bluetooth**: Conecta con dispositivos de medición para obtener datos en tiempo real
- **Monitoreo de parámetros**:
  - Temperatura del suelo
  - Humedad del suelo
- **Captura de imágenes**: Documenta el proceso de compostaje visualmente
- **Interfaz intuitiva**: Diseño simple y fácil de usar para estudiantes
- **Gestión de datos**: Registro y seguimiento del proceso de compostaje

## 🛠️ Tecnologías Utilizadas

- **Android** (Material Design)
- **Bluetooth** para conectividad con sensores
- **Java/Kotlin** (lenguaje de programación)
- Interfaz responsive para dispositivos móviles

## 📱 Capturas de Pantalla

La aplicación incluye:
- Pantalla principal con imagen de la compostera
- Botones de conexión/desconexión Bluetooth
- Visualización de datos de temperatura (PPM)
- Medición de humedad del suelo
- Funcionalidad de cámara para documentar el progreso

## 🚀 Instalación

1. Clona este repositorio:
```bash
git clone https://github.com/Lauracartagena/proyecto-compostera-escolar.git
```

2. Abre el proyecto en Android Studio

3. Sincroniza las dependencias de Gradle

4. Conecta un dispositivo Android o usa un emulador

5. Ejecuta la aplicación

## 📋 Requisitos

- Android 5.0 (API 21) o superior
- Permisos de Bluetooth
- Permisos de cámara
- Permisos de almacenamiento (para guardar imágenes)

## 🔧 Configuración

### Permisos necesarios en AndroidManifest.xml:

```xml
<uses-permission android:name="android.permission.BLUETOOTH" />
<uses-permission android:name="android.permission.BLUETOOTH_ADMIN" />
<uses-permission android:name="android.permission.CAMERA" />
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
```

## 📖 Uso

1. **Conectar dispositivo**: Presiona el botón "CONECTAR" para establecer conexión Bluetooth con los sensores
2. **Monitorear datos**: Visualiza en tiempo real la temperatura y humedad
3. **Capturar imágenes**: Usa el botón de cámara para documentar el estado de la compostera
4. **Desconectar**: Usa el botón "DESCONECTAR" cuando termines

## 🤝 Contribuir

Las contribuciones son bienvenidas. Para cambios importantes:

1. Haz fork del proyecto
2. Crea una rama para tu función (`git checkout -b feature/nueva-funcion`)
3. Commit tus cambios (`git commit -m 'Añadir nueva función'`)
4. Push a la rama (`git push origin feature/nueva-funcion`)
5. Abre un Pull Request

## 🎓 Propósito Educativo

Este proyecto tiene como objetivo:
- Promover la educación ambiental en escuelas
- Enseñar sobre compostaje y sostenibilidad
- Integrar tecnología con prácticas ecológicas
- Desarrollar conciencia ambiental en estudiantes

## 📝 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para más detalles

## 👥 Autores

* **Laura cartagena** - *Desarrollo inicial* - [Lauracartagena](https://github.com/Lauracartagena)

## 🙏 Agradecimientos

- A las instituciones educativas que apoyan este proyecto
- A los estudiantes y profesores que participan en el programa de compostaje
- A la comunidad de desarrollo de Android

## 📞 Contacto

Para preguntas o sugerencias, contacta a: [tu-email@ejemplo.com]

---

⭐️ Si este proyecto te resulta útil, considera darle una estrella en GitHub

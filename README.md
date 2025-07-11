# Proyecto Final - Fundamentos de Computación

**Repositorio:** `Proyecto Final`  
**Descripción:** Sistema de Gestión de Tienda

Este proyecto fue pensado para poner a prueba y en práctica los conocimientos adquiridos a lo largo de la cursada de la materia **Fundamentos de Computación**. La implementación incluye el uso de funciones con punteros, listas, árboles y hashes, entre otras estructuras y conceptos vistos durante el curso.

## Funcionalidades

- Comprar productos
- Cobrar ventas
- Administrar el inventario de productos

Todo esto se realiza de forma sencilla a través de una interfaz medianamente amigable, buscando brindar una buena experiencia tanto auditiva como visual, gracias a la integración de efectos de sonido y efectos visuales.

## Instrucciones de Uso

> **¡Importante!**  
> Para evitar posibles conflictos con rutas previamente configuradas en el código, se recomienda instalar (copiar) la carpeta del proyecto directamente en el disco **C:** de tu computadora.  
>  
> Ejemplo de ruta sugerida:  
> `C:\Fundamentos`

1. Descarga o clona este repositorio en tu computadora.
2. Copia la carpeta del proyecto a la ruta `C:\Fundamentos`.

## Cómo Compilar

- Abre el proyecto en Visual Studio Code.
- Para compilar correctamente el proyecto y generar el archivo `.exe`, presiona **Ctrl + Shift + B**.
- Esto ejecutará la tarea de compilación configurada en VS Code y podrás probar el ejecutable resultante en la misma carpeta del proyecto.

- Si deseas probar el proyecto en Zinjai, puedes descagar solamente su carpeta correspondiente, abre directamente el archivo proyecto.c desde la carpeta correspondiente.

## Requisitos del Sistema

### MinGW-w64 (Requerido)

Para poder compilar y ejecutar este proyecto en VS Code, es **necesario** tener instalado MinGW-w64:

1. https://winlibs.com/#download-release 
2. **Descompresión:** Extrae la carpeta `mingw64` y colócala en una ubicación fácilmente accesible, preferiblemente en el disco C: o en la raíz de otra unidad.
   - Ejemplo de ubicación recomendada: `C:\mingw64`
3. **Configuración del PATH:** Para que el sistema detecte y pueda usar GCC correctamente, debes agregar la ruta `C:\mingw64\bin` (o la ruta donde hayas instalado MinGW) a las variables de entorno del sistema PATH.

#### Pasos para agregar al PATH:
1. Presiona `Win + R`, escribe `sysdm.cpl` y presiona Enter
2. Ve a la pestaña "Opciones avanzadas"
3. Haz clic en "Variables de entorno"
4. En "Variables del sistema", busca y selecciona "Path", luego haz clic en "Editar"
5. Haz clic en "Nuevo" y agrega la ruta: `C:\mingw64\bin`
6. Haz clic en "Aceptar" en todas las ventanas

Una vez configurado correctamente, podrás usar VS Code para compilar proyectos en C sin problemas.

## Dependencias

- Este código fue desarrollado, trabajado y probado únicamente en **GCC** usando **MinGW** para su ejecución en sistemas Windows.
- No se garantiza el funcionamiento en otros compiladores o entornos diferentes a GCC con MinGW.

## Créditos

- Jonathan Misael Lopez
- Barrios Juan Dario

## Posibles mejoras

- Mejorar la portabilidad del sistema para que funcione correctamente en diferentes sistemas operativos y entornos.
- Mejor manejo de interfaces para una experiencia de usuario más fluida y profesional.
- Mejorar el uso de árboles y hashes para optimizar el rendimiento y la organización de los datos.
- Implementar mejores funciones de administración, como control total de los productos y control de empleados.
- Agregar la posibilidad de filtrar productos al comprar, especialmente si la lista es muy extensa.
- Desarrollar un sistema de cobro más realista, permitiendo pagos mediante tarjetas o transferencias.
- Integrar geolocalización en tiempo real para implementar funciones de envíos.
- A futuro, migrar a una interfaz de ejecución más completa que no dependa únicamente del CMD, evitando así las limitaciones actuales (por ejemplo, soporte para tildes, símbolos, emojis amigables, etc.).

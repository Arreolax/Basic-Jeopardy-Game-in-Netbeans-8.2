# Jeopardy Básico (NetBeans 8.2)

## Descripción
Este proyecto implementa un sencillo juego estilo **Jeopardy** desarrollado en Java con NetBeans 8.2. Permite a **dos equipos** competir respondiendo preguntas organizadas en **4 categorías** con **5 preguntas** cada una. Cada respuesta correcta suma puntos al equipo; una respuesta incorrecta los resta.

## Características principales
- **Modo multijugador** (dos equipos).
- **Gestión de puntuaciones** automática.
- **Editor de preguntas** integrado: se pueden añadir, editar o eliminar preguntas personalizadas.
- Interfaz gráfica basada en Swing (generada por el editor de formularios de NetBeans).
- Sonidos de fondo y efectos para respuestas correctas/incorrectas.

## Requisitos
- **Java Development Kit (JDK) 8** (compatible con NetBeans 8.2).
- **NetBeans IDE 8.2** (opcional, pero recomendado para abrir los formularios `.form`).
- Herramientas de línea de comandos de **Ant** (incluidas con NetBeans).

## Compilación y ejecución
1. **Abrir el proyecto** en NetBeans (`File → Open Project` → seleccionar la carpeta `Basic-Jeopardy-Game-in-Netbeans-8.2`).
2. **Compilar** usando *Build → Build Main Project* (o `ant` desde la línea de comandos). El JAR resultante se genera en `Jeapardi/dist/`.
3. **Ejecutar** desde NetBeans (`Run → Run Project`) o ejecutando el JAR directamente:
   ```bash
   java -jar Jeapardi/dist/Jeapardi.jar
   ```

## Personalizar preguntas
El juego incluye una sección **"Personalizar Preguntas"** accesible desde la UI. Allí puedes:
- Añadir nuevas preguntas y respuestas.
- Modificar preguntas existentes.
- Eliminar preguntas que no desees.
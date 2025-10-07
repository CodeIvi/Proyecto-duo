# Guía para agentes AI en Proyecto-duo

Este documento proporciona instrucciones específicas para agentes AI que colaboran en el desarrollo de este repositorio. Sigue estas pautas para maximizar la productividad y mantener la coherencia del proyecto.

## Visión general del proyecto
- El proyecto contiene archivos Java (`Hola.java`, `prueba.java`) y documentación (`prueba.md`).
- No se detectan frameworks, dependencias externas ni estructura de carpetas avanzada; el código es monolítico y simple.
- No existe un README ni documentación de arquitectura, por lo que la comprensión depende de la inspección directa de los archivos fuente.

## Flujos de trabajo críticos
- **Compilación:** Usa `javac Hola.java prueba.java` para compilar los archivos Java.
- **Ejecución:** Ejecuta con `java Hola` o `java prueba` según el punto de entrada.
- **No hay scripts automatizados ni archivos de configuración de build.**
- No se detectan pruebas automatizadas ni convenciones de test.

## Convenciones y patrones
- El código fuente está en la raíz del repositorio.
- No hay convenciones de nombres de paquetes ni modularización.
- Los archivos Java pueden contener el método `main` como punto de entrada.
- No se detectan anotaciones, frameworks ni patrones avanzados.

## Integraciones y dependencias
- No hay dependencias externas ni integración con servicios o APIs.
- No se detectan archivos de configuración para CI/CD, linters, ni herramientas de análisis estático.

## Ejemplo de flujo de trabajo
```bash
# Compilar todos los archivos Java
javac Hola.java prueba.java

# Ejecutar el programa principal
java Hola
```

## Recomendaciones para agentes AI
- Prioriza la claridad y simplicidad en las contribuciones.
- Si agregas nuevas funcionalidades, documenta los puntos de entrada y flujos de ejecución en este archivo.
- Si introduces dependencias externas, crea y documenta un archivo README.md y actualiza esta guía.
- Mantén los archivos fuente en la raíz a menos que se requiera una estructura más compleja.

---

¿Falta información relevante o hay flujos de trabajo que no se han documentado? Por favor, indícalo para mejorar esta guía.
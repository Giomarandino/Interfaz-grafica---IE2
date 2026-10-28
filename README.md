# Interfaz-grafica---IE2
Instancia evaluativa 2
# 🌱 Simulador de Ecosistema — Swing

## 1. Descripción del proyecto

El Simulador de Ecosistema es una aplicación de escritorio desarrollada en Java que permite configurar y observar la evolución de un ecosistema compuesto por plantas, conejos y lobos.

Esta segunda instancia transforma el simulador de consola de la primera instancia evaluativa en una aplicación gráfica utilizando Java Swing y una arquitectura MVC con acceso a datos mediante archivos de texto plano.

La simulación mantiene las reglas de la primera instancia: reproducción, alimentación, caza, envejecimiento, efectos climáticos, intervención del jugador y generación de un reporte final.

## 2. Integrantes

- **Valentina Caramanico**
- **Giovanna Marandino** 
- **Paloma Corbalán** 
- **Docente:** Giuliana Dealbera Etchechoury.

## 3. Tecnologías utilizadas

- Java.
- Java Swing.
- NetBeans IDE.
- JDK.
- Git y GitHub.
- Figma.
- Archivos de texto plano (`.txt`) para guardar y recuperar simulaciones.

## 4. Requisitos para ejecutar el proyecto

- Tener instalado un JDK compatible con el proyecto.
- Contar con NetBeans compatible con la versión de Java utilizada.
- Descargar o clonar este repositorio de GitHub.

## 5. Instrucciones de ejecución

1. Clonar o descargar el repositorio.
2. Abrir NetBeans.
3. Seleccionar **File → Open Project**.
4. Elegir la carpeta del proyecto.
5. Ejecutar la clase principal del proyecto.

## 6. Arquitectura del proyecto

El sistema se organiza en los siguientes paquetes:

- **modelo:** entidades del ecosistema, reglas de simulación, clima, reproducción, mortalidad y estadísticas.
- **vista:** ventanas, formularios, tablas, botones y presentación de eventos mediante Swing.
- **controlador:** coordinación entre la interfaz, el modelo y el acceso a datos; validación de entradas.
- **dao:** guardado y recuperación del estado de la simulación desde archivos de texto plano.
- **Paquete principal (opcional):** punto de entrada de la aplicación, si se decide separarlo del controlador.

La implementación final de cada paquete se documentará una vez completada y verificada.

## 7. Funcionalidades

- Configuración inicial del ecosistema.
- Simulación por turnos.
- Reproducción de plantas y conejos.
- Alimentación de conejos y caza de lobos.
- Efectos de los distintos climas.
- Intervención del jugador cada tres turnos.
- Control de poblaciones y condiciones de colapso.
- Reporte final con nacimientos, muertes y estadísticas.
- Guardado y recuperación de la simulación mediante archivos `.txt`.

**Estado:** las funcionalidades se marcarán como implementadas una vez verificadas en la versión gráfica.

## 8. Diseño UX/UI

**Prototipo de Figma:** https://www.figma.com/design/BFfixiiBMYoSJ0QhFdhzeP/Prototipos-Ecosistema-IE2?node-id=0-1&t=5bO7DYPYat6e164m-1

El diseño contempla las pantallas de configuración, simulación en curso y reporte final, junto con los estados de error y confirmación.

## 9. Video explicativo

**Enlace al video:** 

El video presenta la funcionalidad del sistema, la arquitectura, las decisiones de diseño, las dificultades encontradas y la contribución de cada integrante.

## 10. Desafíos y soluciones

En esta sección se documentarán los principales problemas encontrados durante el desarrollo, las alternativas evaluadas y las soluciones adoptadas por el equipo.

## 11. Uso de IA y documentación consultada

Se registrarán las herramientas de IA utilizadas, los fines para los que se utilizaron y los enlaces a las conversaciones pertinentes. También se incluirán las páginas web y demás documentación consultadas.

La participación individual y las evidencias correspondientes se documentarán de acuerdo con las pautas de la instancia evaluativa.

## 12. Estado del proyecto

**Versión:** 2.ª instancia evaluativa.

**Fecha de entrega:** 4 de noviembre de 2026.

**Estado actual:** en desarrollo.

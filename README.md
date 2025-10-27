# BaseScreenplay 🎭✅
Proyecto base automatización de pruebas con **Serenity BDD**, utilizando el patrón **Screenplay** en **Java** con **Gradle**. Este proyecto sirve como plantilla base para construir pruebas automatizadas de frontend o backend de manera ordenada, limpia y escalable.

---

## 🚀 Tecnologías Utilizadas

| Tecnología        | Descripción |
|-------------------|-------------|
| Java              | Lenguaje de programación |
| Serenity BDD      | Framework para reportes y soporte BDD |
| Screenplay Pattern| Patrón de diseño para automatización |
| Cucumber (opcional)| Permite escribir pruebas en Gherkin |
| Gradle            | Gestión de dependencias y build |
| JUnit             | Framework de pruebas |

---

## 🗂️ Estructura del Proyecto
| Carpeta | Descripción |
|----------|-------------|
| interacciones | Acciones de bajo nivel realizadas por el actor |
| models | Clases de datos o DTOs |
| questions | Validaciones o verificaciones |
| tasks | Flujo de acciones que realiza el actor |
| userinterfaces | Mapeo de elementos de la interfaz |
| utils | Funciones de utilidad |
| runners | Configuración de ejecución de pruebas |
| stepsDefinitions | Definición de pasos para Cucumber |
| features | Escenarios escritos en Gherkin |
| data | Archivos .csv o datos de prueba |
| serenity.conf | Configuración del proyecto Serenity BDD |

---

## ⚙️ Configuración del archivo build.gradle

El archivo `build.gradle` gestiona las dependencias, plugins, compilación y configuración del proyecto.


---

## 📦 Prerrequisitos

Antes de ejecutar este proyecto, asegúrate de tener instalado:

- Java JDK 11 o superior 
- Gradle (opcional)
- IntelliJ IDEA o Eclipse
- Git

---

## ⚙️ Configuración del Proyecto

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/RonaldBeltran1222/BaseScreenplay.git
   cd BaseScreenplay


---

## ⚙️ Mantenimiento de versiones

En la pagina de https://mvnrepository.com/ se pueden encontrar las dependencias si se dea actualizar o modificar el numero de versión de las usadas en el proyecto.

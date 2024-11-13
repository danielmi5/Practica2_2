# Parte individual: Entornos de Desarrollo y Configuración de IDEs

## 2.1. Instalación de Entornos de Desarrollo, Propietarios y Libres (CE 2.a)

### Tarea
He instalado dos entornos de desarrollo: **Visual Studio Code (VSC)** y **CLion**.

### Proceso de Instalación
1. **Visual Studio Code (VSC)**:
   - Se descarga desde la página oficial.
   - Al finalizar la instalación, se abre automáticamente.

2. **CLion**:
   - Instalación desde **JetBrains Toolbox**.
   - Se instala de manera directa sin necesidad de configuración adicional.

### Preguntas Evaluativas

- **Diferencias en el Proceso de Instalación**:
  - JetBrains es más profesional, con una aplicación que gestiona todas las herramientas de forma rápida.
  - VSC permite una instalación más configurable, especialmente en aspectos como la ruta de la carpeta y las tareas adicionales.

- **Ventajas en la Instalación**:
  - **JetBrains (CLion)**: Interfaz unificada para gestionar todas las herramientas, más fácil de usar.
  - **VSC**: Ofrece mayor configurabilidad, pero el proceso es ligeramente más largo.

### Evidencias:
- Captura de pantalla de la instalación de **VSC** y **CLion**.

---

## 2.2. Gestión de Módulos y Extensiones en el Entorno de Desarrollo (CE 2.b)

### Tarea
Instalación de extensiones en ambos IDEs:

- **VSC**:
  - **Pylance**: Proporciona características avanzadas para Python, como los docstrings.
  - **Python**: Para facilitar la ejecución y depuración de código Python.
  - **Prettier**: Para formatear el código.
  - **Live Server**: Para ver los cambios en tiempo real.

- **CLion**:
  - **AI Assistant**: Ayuda en el desarrollo del código.
  - **Rust Plugin**: Soporte para el lenguaje Rust.

### Preguntas Evaluativas

- **Proceso de Instalación de Extensiones**:
  - **VSC**: Instalación directa desde el panel de extensiones, fácil de usar.
  - **CLion**: La instalación de plugins también es directa, pero algunos son de pago y requieren una licencia.

- **Beneficios de las Extensiones**:
  - **VSC**: Mejora en la productividad, especialmente con las herramientas de depuración y formateo de código.
  - **CLion**: Mejora en la experiencia de desarrollo en C/C++, especialmente con la ayuda del asistente de IA.

### Evidencias:
- Captura de pantalla de las extensiones instaladas en **VSC** y **CLion**.

---

## 2.3. Personalización y Automatización del Entorno (CE 2.c)

### Tarea
Personalización y automatización de tareas:

1. **Visual Studio Code (VSC)**:
   - Personalización mediante `settings.json` y `keybindings.json`.
   - Modificación del tema y de los atajos de teclado.
   - Automatización de pruebas con `task.json` para ejecutar pytest.

2. **CLion**:
   - Personalización de temas y atajos mediante la configuración del IDE.
   - Automatización de tareas también se puede hacer, pero es más limitada en comparación con VSC.

### Preguntas Evaluativas

- **Aspectos Personalizados**:
  - **VSC**: Personalización completa del entorno (temas, atajos de teclado, y extensiones).
  - **CLion**: Menos personalización, pero suficiente para un desarrollo eficiente en C/C++.

- **Configuración de la Automatización de Tareas**:
  - **VSC**: Automatización mediante tareas personalizadas en el archivo `task.json`, muy útil para las pruebas con pytest.

### Evidencias:
- Capturas de pantalla mostrando la personalización y automatización en **VSC** y **CLion**.

---

## 2.4. Configuración del Sistema de Actualización del Entorno de Desarrollo (CE 2.d)

### Tarea
Configuración de actualizaciones automáticas:

1. **Visual Studio Code (VSC)**:
   - Activación de actualizaciones automáticas en la configuración de la aplicación.

2. **CLion**:
   - Las actualizaciones se gestionan desde **JetBrains Toolbox**, con opción para mantener versiones anteriores.

### Preguntas Evaluativas

- **Configuración de Actualizaciones Automáticas**:
  - **VSC**: Se activa en la configuración, en la opción "Actualizar automáticamente".
  - **CLion**: Gestionado a través de **JetBrains Toolbox**, con opción de actualización automática.

- **Importancia de Mantener el IDE Actualizado**:
  - Mantener el IDE actualizado garantiza nuevas funcionalidades, corrección de errores y mayor seguridad.

### Evidencias:
- Captura de pantalla de la configuración de actualizaciones en **VSC** y **CLion**.

---

## 2.5. Generación de Ejecutables a partir de Código Fuente en Distintos Lenguajes en un Mismo IDE (CE 2.e)

### Tarea
Escribir un programa que cuente de 10 a 0 y luego imprima "¡Despegue!" en **VSC** para Python y Java.

### Preguntas Evaluativas

- **Proceso para Ejecutar el Programa en Diferentes Lenguajes**:
  - **Python**: Requiere la instalación del intérprete de Python y la extensión de Python en **VSC**.
  - **Java**: Se necesita el JDK y una extensión para facilitar la ejecución.

- **Diferencias en la Generación del Ejecutable**:
  - **Python** no genera un ejecutable como tal; se ejecuta directamente.
  - **Java** genera un archivo `.class` que contiene el bytecode y puede ejecutarse independientemente de la terminal.

### Evidencias:
- Captura de pantalla mostrando la ejecución del programa en ambos lenguajes en **VSC**.

---

## 2.6. Generación de Ejecutables con Diferentes IDEs a partir del Mismo Código Fuente (CE 2.f)

### Tarea
Escribir un programa en Python que cuente de 10 a 0 y luego imprima "¡Despegue!" en **VSC** y **CLion**.

### Preguntas Evaluativas

- **Diferencias en la Ejecución del Código**:
  - **CLion** no es tan eficiente para ejecutar Python debido a que está más optimizado para C/C++. Necesita configuraciones adicionales.
  - **VSC** es más eficiente y cómodo para manejar múltiples lenguajes de programación, incluido Python.

- **IDE Más Cómodo y Eficiente para Python**:
  - **VSC** es más eficiente debido a su mejor soporte para múltiples lenguajes, incluidas las extensiones específicas para Python.

### Evidencias:
- Captura de pantalla mostrando la ejecución del programa en ambos IDEs.

---

**Conclusión**: 
He explorado dos entornos de desarrollo (Visual Studio Code y CLion), cada uno con características únicas. **VSC** es más flexible y eficiente al manejar diferentes lenguajes de programación, mientras que **CLion** está más optimizado para C/C++, aunque su uso con otros lenguajes, como Python, no es tan cómodo. La personalización, automatización de tareas y actualización de los entornos son factores clave para mejorar la productividad del desarrollo.

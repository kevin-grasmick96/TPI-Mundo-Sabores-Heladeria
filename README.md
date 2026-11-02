# 🍦 Control de Stock - Heladería "Mundo Sabores"
**Trabajo Práctico Integrador (TPI) - Entrega N.° 4**  
**Asignatura:** Organización Empresarial  
**Carrera:** Tecnicatura Universitaria en Programación a Distancia (TUP AD)  
**Institución:** Universidad Tecnológica Nacional (UTN)

---

## 📌 Integrantes y Equipo de Trabajo
* **Alumno:** Grasmick, Kevin Sebastián  
* **Rol:** Desarrollador / Administrador de Sistemas (Único desarrollador)

### 👨‍🏫 Cuerpo Docente
* **Docente Titular:** Prof. Gabriela Martínez  
* **Docente Tutor:** Daniel Eduardo Martínez  

---

## 🚀 Descripción del Software

El **Módulo de Control de Stock** es una solución informática desarrollada en **Python** diseñada para automatizar y optimizar la gestión de inventario de la heladería artesanal **"Mundo Sabores"** (ubicada en General Racedo, Entre Ríos). 

El sistema reemplaza los registros manuales en papel por un control digital y centralizado, permitiendo:

* **Gestión de Inventario en Tiempo Real:** Registrar de manera rápida el stock actual de postres helados, categorías y presentaciones.
* **Control de Entradas y Salidas:** Procesar lotes de productos y actualizar automáticamente las existencias a medida que se concretan las ventas.
* **Alertas Automáticas de Reposición:** Monitorear el inventario crítico y emitir avisos cuando las unidades alcancen el umbral mínimo (`stock_minimo`), facilitando la comunicación oportuna con proveedores para evitar quiebres de stock.

---

## 🛠️ Estructura del Repositorio y Versionado (Git & GitHub)

Este proyecto aplica las mejores prácticas de control de versiones y flujo de trabajo colaborativo:

* `main`: Rama principal protegida que contiene las entregas estables y la documentación final.
* `feature/control-stock-v1`: Rama de desarrollo utilizada para la codificación del módulo principal y pruebas unitarias.

### 🔀 Pull Request Auditado
* **PR #1:** `Merge feature/control-stock-v1 into main`
* **Descripción:** Integración del módulo de lectura, parsing, lógica de alerta de reposición y diccionario de datos preliminar (`PRODUCTO`, `STOCK`, `PROVEEDOR`).

---

## 📋 Gestión del Proyecto (Backlog Ágil)

La planificación y seguimiento del proyecto se realiza a través del tablero interactivo **GitHub Projects** utilizando metodología Kanban:

👉 **[Acceso al Tablero de GitHub Projects](https://github.com/users/kevin-grasmick96/projects/2/views/1) 

### 📝 Historias de Usuario (HU)

1. **HU-01: Alerta Automática de Faltantes**
   > *Como* encargado de administración, *quiero* recibir una alerta automática cuando el stock esté por debajo del límite crítico, *para* solicitar reposición a los proveedores a tiempo sin quedarme sin producto.
   > **Estado:** `Done (Listo)`

2. **HU-02: Registro Rápido de Stock en Venta**
   > *Como* empleado de atención al cliente, *quiero* registrar las ventas del día desde la interfaz, *para* actualizar el inventario automáticamente y reducir errores de carga manual.
   > **Estado:** `Done (Listo)`

3. **HU-03: Consulta de Productos Disponibles**
   > *Como* cliente de la heladería, *quiero* consultar el catálogo e informar si hay stock de mis sabores preferidos, *para* concretar mi compra de manera rápida y sin demoras.
   > **Estado:** `In Progress (En Progreso)`

---

## 📈 Indicadores de Control y Auditoría Técnica

Para asegurar la calidad operacional del sistema, se establecen los siguientes estándares:

| Indicador | Estándar de Desempeño | Mecanismo de Auditoría |
| :--- | :--- | :--- |
| **Tiempo Medio de Procesamiento (TMPS)** | Procesar lote de 10 productos en $\le 30$ segundos. | Log de ejecución del software con marca temporal. |
| **Tasa de Error en Registro (TERI)** | Precisión de datos superior al $98\%$. | Arqueos semanales cruzados entre stock físico en freezers y base de datos. |
| **Disponibilidad del Sistema (Uptime)** | $99.5\%$ durante horario comercial. | Monitor de peticiones local / servidor. |

---

## 🤖 Declaración de Transparencia sobre el Uso de Inteligencia Artificial

De acuerdo con las pautas de transparencia de la cátedra de Organización Empresarial:

* **Herramientas utilizadas:** Inteligencia Artificial Generativa (Modelo Gemini / NotebookLM).
* **Propósitos específicos:** 
  * Asistencia en la formalización visual y estandarización del organigrama piramidal y diagrama de Gantt.
  * Corrección de estilo, estructuración del marcado Markdown y revisión de la sintaxis estándar de compuertas BPMN e Historias de Usuario.
* **Responsabilidad Intelectual:** Todo el análisis conceptual, la adaptación al caso real de la heladería "Mundo Sabores", la definición de entidades, la delimitación del alcance y las decisiones de diseño provienen del trabajo crítico y autoría exclusiva del alumno.

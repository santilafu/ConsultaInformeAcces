# 📊 Proyecto de Informes Avanzados en Microsoft Access - Northwind Traders

Este repositorio contiene la práctica final de la **Unidad 5: Confección de Informes**, desarrollada como parte del ciclo de **Desarrollo de Aplicaciones Multiplataforma (DAM)**.

El objetivo principal del proyecto ha sido diseñar e implementar un informe de gestión profesional utilizando una base de datos relacional real (**Northwind Traders**), aplicando lógica de negocio, filtrado de datos y técnicas de diseño visual.

---

## 🚀 Funcionalidades Implementadas

El informe final (`Informe_Productos_VFinal`) ha sido diseñado cumpliendo estrictos requisitos de negocio:

### 1. Filtrado y Lógica de Datos (SQL)
- Se ha implementado una **consulta de selección previa** para limpiar los datos antes de presentarlos.
- **Filtro de Calidad:** Solo se muestran productos con un coste estándar superior a **10€**, eliminando artículos de bajo valor.
- **Join de Tablas:** Integración de las tablas `Products` y `Categories` para mostrar nombres descriptivos en lugar de IDs numéricos.

### 2. Estructura y Agrupamiento
- **Agrupamiento por Categoría:** Los productos se presentan organizados en bloques lógicos (Bebidas, Condimentos, Lácteos, etc.) para facilitar la lectura.
- **Totales en Cabecera:** A diferencia del estándar, se ha personalizado el diseño para calcular y mostrar la **Suma de Costes** (`Sum([Standard Cost])`) al inicio de cada grupo, permitiendo una visión rápida del impacto económico de cada categoría.

### 3. Elementos Avanzados e Incrustados
- **Sub-informe de Pasta:** Se ha creado e incrustado un informe secundario al final del documento que filtra y lista específicamente los productos de la categoría *"Pasta"* (ej. Noquis, Ravioli), demostrando la capacidad de anidar informes.
- **Gráficos de Datos:** Visualización comparativa de precios integrada en el informe (según disponibilidad de la versión).

---

## 🛠️ Tecnologías y Herramientas

* **Entorno:** Microsoft Access 2007/2016 (Motor de base de datos ACE/Jet).
* **Base de Datos:** Northwind Traders (Edición de Escritorio 2007).
* **Lenguajes:** SQL (para las consultas subyacentes) y expresiones de Access para los controles calculados.

## 📂 Estructura del Repositorio

| Archivo | Descripción |
| :--- | :--- |
| `Consulta_Informe_VFinal.pdf` | **Muestra del resultado**. Exportación en PDF del informe generado para visualización rápida sin necesidad de Access. |
| `README.md` | Documentación técnica del proyecto. |

## 📖 Instrucciones de Uso

Para probar el proyecto en local:

1.  Clona este repositorio o descarga el archivo `.accdb`.
2.  Abre el archivo con **Microsoft Access**.
3.  Si se solicita, haz clic en **"Habilitar contenido"** (necesario para las macros de Northwind).
4.  En el panel de navegación, busca la sección **Informes** y ejecuta: `Informe_Productos_Final`.

---
- Autor: Santiago Lafuente Hernández

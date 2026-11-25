# NovaMarket 

Trabajo de **QA manual** realizado en una simulación laboral sobre **NovaMarket**, una tienda online (e-commerce) desarrollada por un equipo interdisciplinario: backend, frontend, mobile, PM y UI/UX.

Este repositorio reúne los dos entregables de mi trabajo como QA:

| Archivos |
| 📊 `NovaMarket_TrazabilidadyCasosdePrueba_QA.xlsx` | Casos de prueba, trazabilidad y reportes de bugs |
| 📄 `InformeQA_NovaMarket.pdf` | Informe final con el estado del proyecto, pensado para público no técnico |

---

## 🛒 Sobre el proyecto

NovaMarket permite recorrer una tienda online completa: explorar un catálogo, armar un carrito, comprar y administrar los productos desde un panel de administración. El objetivo era llegar a una primera versión funcional (MVP) lista para salir a producción.

**Mi rol:** sumarme al equipo pocos días antes de la entrega final, ponerme al día con el trabajo previo del QA anterior, priorizar según el tiempo disponible y asegurar la calidad de todo el flujo de compra.

**Áreas probadas:** Catálogo (categorías y filtros) · Carrito y cálculos · Checkout y confirmación · Panel de administración · Flujo completo E2E.

**Alcance:** pruebas funcionales manuales en ambiente DEV. Quedaron fuera pruebas de carga, seguridad especializada, pasarelas de pago reales y pruebas aisladas de API.

---

## 📊 Excel de casos de prueba

Un libro con una hoja por módulo y hojas de seguimiento. Cada caso de prueba incluye:

`ID` · `título` · `descripción` · `condiciones iniciales` · `pasos a seguir` · `postcondiciones` · `resultado esperado` · `resultado obtenido` · `severidad` · `prioridad` · `estado de ejecución` · `tester` · `fecha de ejecución` · `entorno`

| Hoja | Contenido |
|---|---|
| **Trazabilidad Casos** | Resumen de métricas por módulo (total, aprobados, fallidos, bugs, % ejecutado) y una tabla que conecta cada caso con el criterio de aceptación que valida, su tipo, prioridad, severidad, estado y bug asociado. |
| **Casos Reportados** | Registro de bugs con pasos para reproducirlos, resultado esperado vs. obtenido, severidad, prioridad, evidencia, estado y caso de prueba relacionado. |
| **Pruebas E2E** | Recorridos completos de compra: registro, login, catálogo, detalle, carrito, checkout y confirmación. |
| **Categorías y Filtros** | Casos del catálogo: carga de productos, filtros por categoría y búsqueda. |
| **Carrito y Cálculos** | Casos del carrito: agregar, quitar, cantidades, importes, persistencia y límite de stock. |
| **Checkout** | Casos de compra: acceso con sesión, creación única del pedido y confirmación. |
| **Modulo admin** | Casos del panel de administración: acceso restringido, alta, edición y baja de productos, consulta de pedidos y recorridos admin–cliente. |

**Tipos de prueba aplicados:** funcionales, E2E, negativas, de borde, de integración, de validación de alcance y visuales.
**Criterios usados:** prioridad `P0 – Crítica`, `P1 – Alta`, `P2 – Media` y severidad `Crítica`, `Alta`, `Media`, `Baja`.

---

## 📄 Informe final (PDF)

Un informe visual y didáctico, escrito en lenguaje simple para que lo entienda cualquier persona, sin perfil técnico. Incluye:

- **Resumen ejecutivo** con indicadores clave y glosario.
- **Gráficos:** tortas y barras de resultados, índices de calidad, prioridad, severidad, tipos de prueba y bugs.
- **Detalle módulo por módulo** de lo que se verificó.
- **Bugs encontrados** y su estado.
- **Capturas del Excel** como evidencia del trabajo.
- **Devolución final:** qué salió bien, qué falta resolver, próximos pasos recomendados y límites de la ronda de pruebas.
- **Anexo** con el avance de las pruebas en días.

---

## 📈 Resultados en números

| Indicador | Valor |
|---|---|
| Casos de prueba ejecutados | **38** (100% del plan) |
| Casos aprobados | **37** (97,4%) |
| Casos fallidos | 1 |
| Bugs reportados | **3** (2 cerrados y 1 crítico en corrección) |
| Jornadas de ejecución | 3 (11, 17 y 18 de noviembre de 2026) |

**Hallazgo principal:** al confirmar una compra, el stock de los productos no se descontaba, lo que podía provocar sobreventa. Se reportó como bug crítico (BUG-001) y se recomendó resolverlo antes del lanzamiento.

---

## 🧰 Qué muestra este trabajo

- Diseño de casos de prueba con **trazabilidad** hacia los criterios de aceptación.
- **Priorización** por riesgo de negocio con poco tiempo disponible.
- Pruebas **E2E** del flujo completo de una compra real.
- **Reporte de bugs** claro, reproducible y con evidencia.
- **Comunicación** de resultados a perfiles técnicos y no técnicos.

---

## 👩‍💻 Autora

**Celeste Vidotto** · QA Tester
🔗 LinkedIn: _[agregar enlace a tu perfil]_

> Proyecto realizado con fines de aprendizaje, en el marco de una simulación laboral.

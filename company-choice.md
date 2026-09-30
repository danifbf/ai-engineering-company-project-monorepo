# Compañia: Brasaland
- Eligo esta cadena de restaurantes Brasaland porque es un CRM, lo cual se trata con personas diariamente y e implica mayor complejidad.
- A la par indica que trabaja en multiples paises.
- Quizás tambien se deba hacer un Organigrama con el nombre de los departamentos y personas que trabajan en ellos junto los años
- Ademmás revisando las funciones que tienen cada departamente y sus problemas, se deberá aportar una solución más adelante, ya que dice que todos los restaurantes se encuentran aislados de los demás.

## El reto
Brasaland opera una cadena de restaurantes distribuida en varios países, con procesos críticos que funcionan de manera aislada entre sí: operaciones, compras, formación y control de calidad. Esta falta de integración provoca ineficiencias operativas, duplicación de tareas, errores en la ejecución diaria, falta de visibilidad corporativa y dificultad para escalar la cadena de forma ordenada.

El reto consiste en diseñar e implementar un sistema de inteligencia artificial corporativo capaz de:
- Unificar datos dispersos en una plataforma centralizada.
- Estandarizar procesos operativos y de formación en todos los locales.
- Automatizar la detección de problemas y la generación de recomendaciones.
- Facilitar la toma de decisiones basada en datos en tiempo real.
- Reducir la dependencia de procesos manuales y documentos desorganizados.

## My AI Agent Idea
https://github.com/danifbf/ai-engineering-company-project-monorepo.git

Posibilidades a mejorar
 1) **Operaciones de restaurante**": Se observa que cada uno de los 14 locales opera en gran medida de forma aislada. **No hay visibilidad centralizada** por lo que provoca exceso de stock en algunos locales y roturas en otros.
    - Necesidad: **Implementar un data warehouse corporativo que consolide**:
        - Ventas por local y por categoría
        - Inventarios y rotación de productos
        - Previsiones de demanda
        - Métricas operativas en tiempo real

 2) **Compras y proveedores**": Con alrededor de 20 proveedores entre Colombia y Florida, se entera de los cambios en el precio de las materias primas cuando llega la factura. No existe ningún dato consolidado de compras a nivel de cadena. 
    - Necesidad: **Centralizar la información de compras mediante**:
        - OCR + extracción estructurada de facturas
        - Normalización de precios, unidades y categorías
        - Detección automática de variaciones y anomalías
        - Reportes ejecutivos y dashboards financieros + KPI

 3) "**Formación y estándares de calidad**": Todos los locales deben seguir las mismas recetas, técnicas de preparación y estándares de presentación independientemente del país. Un Google Drive compartido que nadie sabe navegar que **cuando cambia una receta o un procedimiento**, comunicar la actualización a los 14 locales en dos idiomas lleva días y suele generar confusión.
    - Necesidad: **Crear un repositorio estructurado y versionado de SOPs, recetas y estándares, con**:
        - Versionado automático de documentos
        - Traducción EN/ES integrada
        - Notificaciones automáticas a los locales
        - RAG para consultas operativas del personal
## Checklist de Tareas y Enlaces (LOD)

- **Reconciliación y Enlace (LODRefine):** Sí. Se han reconciliado las instancias del dataset con fuentes externas de Linked Data (como Wikidata u otras) identificando los elementos enlazables.
- **Propiedad `owl:sameAs`:** Sí. Todos los ficheros RDF generados incorporan la propiedad `owl:sameAs` conectando recursos locales del dataset con recursos externos.
- **Actualización de Mapeos RML:** Sí. Se han adaptado los mapeos previos para reflejar las nuevas columnas con los enlaces externos generados.
- **Generación de RDF (Turtle):** Sí. Se ha transformado el dataset completo a RDF utilizando la sintaxis Turtle (`.ttl`).
- **Consultas SPARQL de Verificación:** Sí. Se han incluido consultas SPARQL que hacen uso de la ontología, emplean los enlaces `owl:sameAs` y devuelven resultados no vacíos.

## Entregables en GitHub
- [x] Fichero JSON con las operaciones de enlace (`lodrefine/*-with-links.json` bajo el directorio `lodrefine/`).
- [x] Fichero CSV actualizado con enlaces (`csv/*-with-links.csv` bajo el directorio `csv/`).
- [x] Fichero RML actualizado (`mappings/*-with-links.rml` bajo el directorio `mappings/`).
- [x] Fichero RDF en sintaxis Turtle (`rdf/*-with-links.ttl` bajo el directorio `rdf/`).
- [x] Fichero de consultas SPARQL (`rdf/queries-with-links.sparql` bajo el directorio `rdf/`).
- [x] Autoevaluación (`selfAssessmentHandsOn5.md` en la raíz del directorio del grupo).

# From Monolingual Multiword Expression Discovery to Multilingual Concept Enrichment: an Ontology-based Approach

Repository for the semantically-enriched resource created on the basis of biographic texts for 500 agent entities scraped from the Europeana portal. The enrichment added the following information:
1. MWE discovered through the combination of AKE and linguistic patterns,
2. DBpedia-correlated entities linked to similar MWEs,
3. multilingual labels for the Dbpedia entities, for all available languages,
4. broader concepts for each of the Dbpedia entity linked to a specific MWE.

The resource is stored in a json file, where each key represent the Dbpedia uri of the agent entity. For each of these entity, the **mwes** key is used to store the top-5 recollected MWEs, ranked by a custom score while the **closestConcepts** key stores uris and multilingual labels for the mwes that show a strong connection to specific links in Dbpedia.


### Authors
Gennaro Nolano[^1] 
Maria Pia di Buono[^1]    
Johanna Monti[^1]  
[^1]: Unior NLP Research Group, University of Naples "L'Orientale"

### Contacts
gnolano@unior.it

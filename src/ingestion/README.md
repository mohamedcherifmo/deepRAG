# Ingestion

The primary module in this package should use Graph Maker to populate an existing ontology as a graph database.

Additionally, content should be generated using the LLM for multiple modalities, given an ontology of topics as entities.

For generating sufficient test data, projections should be calculated for the "real" data generated by the LLM and indexed into the Vector DB.
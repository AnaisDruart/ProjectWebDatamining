# ProjectWebDatamining

This project is a large and long practical exercise that consists in integrating all the pieces that have been seen during the first sessions into a consolidated application.

**Main objective**
* Make a (Web) application that integrates geospatial data from mutiple sources, including dynamic data.
* Define a knowledge model (that is, an ontology) that describes the types of entities that are stored in the data base.
* Optional: Display information on Web pages together with structured data, for best search engine optimisation.

**Steps involved**
* Setup a triplestore. We choose to use Apache Jena Fuseki
* Define e a vocabulary for describing geolocated resources. 
* Convert static data (from open data sources) into RDF, and load the resulting data to the triplestore. You can simply generate an RDF file that you load manually to the triplestore, or (better) add the RDF programmatically using SPARQL Update queries.
* Make a website that will allow one to select places such as a city (in a list or on a map) and get the associated data. Ideally, provide links to nearby resources, or allow the selection of resources by types (e.g., hospitals, train stations). The resulting lists and entities should be available in HTML with RDF. 


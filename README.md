MatOnto-Ontologies
==================

Ontologies for the MatOnto Project serialized in [Turtle](http://www.w3.org/TeamSubmission/turtle/).


Editing
-------

We use [Protege](http://protege.stanford.edu/) to edit our ontologies.  We recommend you do the same to keep style consistent.  If you feel so inclined, you may edit them by hand.


Deploying
---------
1. Make changes to `matonto.ttl`
3. Open `matonto-build.ttl` in Protege
4. Refactor -> Merge Ontologies
5. Name resultant file `matonto-release.ttl`
6. Commit / Push changes
7. Publish using MatRest/owl/publish and Raw URL 

Raw URL: `https://raw.githubusercontent.com/iNovexIrad/MatOnto-Ontologies/master/matonto-release.ttl`

At this point if the ontology validated, there will be a new distribution of the ontology in CKAN.  Use the "Load" Button in CKAN to update Stardog/MatOnto

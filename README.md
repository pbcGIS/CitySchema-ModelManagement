# CitySchema-ModelManagement
## Tools and procedures for managing a collection of geographically referenced 3D building models.

The CitySchema city model architecture provides a Digital Asset Management framework for developing, maintaining and sharing city models as modular collections of detailed terrain, ground-plan and building, bridge and wall models. The tool-kit provided in this git-hub repository is concerned with the management og a collection of 3D models representing the current, historical and future buildings, bridges and walls. [https://pbcgis.github.io/CitySchema-Bos3d-RepositoryCatalog/catalog/model_collection.htm](Click here to learn more about the citySchema model collection). Or here to [https://pbcgis.github.io/CitySchema-Bos3d-RepositoryCatalog/catalog/doc_index.htm](learn more about the overall citySchema sharing scheme).  

Managing city-model data on an on-going basis tends to be overwhelming due to the number of diverse source files that have to be processed in regular and repetitive ways, and the constant decisions about where to put information that you want to be able to find again, coupled with the nagging feeling that you may heve deleted or failed to save some models, but find that it can be very difficult to figure out whether you did or not.  3D models are trickier to handle than points, lines and polygons.  It is harder to approach the editing task in a care-free way.  There are some new tools and trouble-shooting steps that an other-wise wxperienced GIS person will have to learn.   

None of this is rocket science, but it takes time and persistence to come up with a storage scheme that can grow in extent and depth without growing more difficult to manage.   While there may be more than one way to manage such a collection of assets, it is best to follow a method that is well documented so that role of model curator and the assets themselves can be handed from one employee or software vendor to another without irreplaceable knowledge beinbg lost.

The citySchema project is about working through many of these problems from end-to-end and to providing a well documented tools and procedures in hopes that more people and organizations will debvelope, preserve and share their city model assets.

The tools and procedures that are shared here are based on an ArcGIS Pro geoprocessing tools and Tasks, and geodatabase data management architecture.  The basic collection management patterns, which are documented in the wiki for this github site could also be created for other software.  

Use Cases:
* Intake and enrollement of new models in a variety of formats and coordinate systems
* Produce new building, bridge and wall models using GIS. 
* Establish and preserve model-specific information reflecting provenance, links to pertinent references
* Update status for models advancing through review process.
* Downgrade status and modify existing models affected by change.
* Preserve models that reflect past scenarios.
* Preserve source files in predictable archive file system. 
* Publish next edition of model collection ready for production of web scenes, tiled sketchup and open-format archive. 
* Systematically audit and repair models using open-source archival formats. 

Features a completely auditable and reversable stage, commit and rollback model for all changes. 



This test case accompanies the authors work on A New Approach for Validation of CIM Datasets Using SHACL

The following folders represent:
.\"CGMES datasets" : single files, each of which represents a model that is instance of some CIM RDFS file.
.\"CIM RDFS" : CGMES CIM RDF Schema files.
.\"datasets - all with CIM RDFS" : each file represents a dataset - union of all files from "CGMES datasets" with certain CIM RDFSs included (which are designated in the name of a file). Validation report subfolder contains a result of validation of a dataset with coresponding shacl file. 
.\"datasets - with CIM RDFS" : each file represents a dataset created from an initial CGMES dataset with all CGMES datasets it depends on (which is determined by profile dependencies) as well as all needed CIM RDFSs. Validation report subfolder contains a result of validation of a dataset with the corresponding shacl file. 
.\"SHACL shapes" :  contains SHACL shape files each of which is based on corresponding CIM RDFS files.
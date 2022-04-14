# 3D-RDF

Visualizations of RDF graphs in 3-D

## NOTE

This is a preliminary repo. The code has been copied from [3dShEx](https://github.com/weso/3dshex). The aim is to create something similar for RDF graphs.

## How to use

Install with the following command:

```
npm install 3drdf
```

Once installed, import the function. For instance:

```
import rdfTo3D from "3drdf";
```

This function creates a 3DGraph in the specified component, given a RDF.

```
rdfTo3D(rdf, "3dgraph"); 
```

In this example, we are passing as a parameter a String variable (_rdf_) which contains an RDF value,
as well as the reference to a \<div\> ID  (_3dgraph_) .

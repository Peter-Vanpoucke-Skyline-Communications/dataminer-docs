# About the DataMiner Connectivity Framework

With the DataMiner Connectivity Framework, you can set up element connectivity. This means that you can configure and visualize signal paths throughout your infrastructure.

In the element protocol, in/out interfaces can be defined, which allow two types of connections to be made in DataMiner:

- Internal connections: connections within the same element.

- External connections: connections from one element to another.

Connections can be set in different ways:

- In Cube, in the element’s *Properties* window or the DCF configuration window. See [Configuring element connectivity in Cube](Configuring_element_connectivity_in_Cube.md).

- In the matrix interface of a matrix element. See [Configuring matrix parameters](../../part_2/parameters/Configuring_matrix_parameters.md).

- In Visual Overview. See [Implementing DataMiner Connectivity Framework functions](../../part_2/visio/Implementing_DataMiner_Connectivity_Framework_functions.md).

- In *Connectivity.xml* files in the folder *C:\\Skyline DataMiner\\Connectivity*. See [Defining connectivity chains in XML files](Defining_connectivity_chains_in_XML_files.md).

- By importing connection data from an external source (e.g. a configuration management database).

- By means of automatic detection (via a DataMiner App, e.g. IP Network Manager).
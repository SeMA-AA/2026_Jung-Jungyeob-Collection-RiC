# Collection Visualization Beta

## 1. Overview

The Collection Visualization Beta of Art Archives, Seoul Museum of Art (SeMA AA) is an ontology graph visualizing its holdings using Records in Contexts (RiC). All concepts related to the collection are represented as circular nodes—key points of connection—with lines indicating the relationships between them. This includes not only collection items, authority records, and thesauri, but also previously unlinked concepts such as artworks, departments, and regulations. Through the Collection Visualization Beta, users can explore and understand at a glance the contexts in which collection items were created, acquired, and utilized.

![Entity and relationship exploration in Collection Visualization Beta](./images/image1.jpg)

## 2. Purpose and Pilot Collection of the Collection Visualization Beta

- Purpose of the Collection Visualization Beta
  - Restructuring Relationships from a Collection-Centered to a Workflow-Centered Approach
    - Entities and relationships were reorganized around workflows such as acquisition, registration, management, and utilization to illustrate how collections are formed and used.
  - Clarifying Relationship Structures through Core Workflow Models
    - Ten representative models were developed to categorize key relationships within each workflow, distinguishing common structures shared across workflows from the unique characteristics of individual activities.
  - Expanding Entities and Relationships to Reflect the Characteristics of Art Archives
    - Based on RiC-CM, a new Artwork entity and additional relationships were defined to provide a more detailed representation of the contexts surrounding workflows, artworks, and art archival materials.
- Collection Selected for the Collection Visualization Beta
  - The Jung Jungyeob Collection was selected for its potential to illustrate the processes of acquisition, management, and utilization, as well as diverse relationships between artworks and art archival materials.
    - A collection whose entities and relationships were established by applying RiC-CM in the existing Collection Visualization Beta.
    - A collection that documents acquisition and registration processes, including acquisition, appraisal, donation, accessioning, and registration.
    - A collection that provides information on the management history of collection items, including storage facilities, transfers of administrative responsibilities, and archival storage management.
    - A collection that has been utilized in various ways, including public access, consultation, loans, exhibitions, and educational programs.
    - A collection that can be linked to artworks held by SeMA and related art archival materials.
    - A collection that provides information on relationships among individuals, departments, regulations, systems, and institutional records involved in archival workflows.
    - A collection currently available through the Collection Visualization service.

## 3. Development Process of the Collection Visualization Beta

- Analysis of Entities and Relations in Existing Collections
  - We compared and analyzed the entities and relations established by applying RiC-CM to the Jung Jungyeob and Lim Dong-sik Collections to examine the characteristics and limitations of the existing models. Recurring entities and relations were identified, and key elements required for workflow-based modeling were derived.
- Development of Core Workflow Models
  - We analyzed workflows such as acquisition, registration, management, and utilization, and reorganized entities and relations around the agents responsible for each workflow, the objects involved, applicable regulations, and related records. As a result, ten core workflow models were developed, reflecting both common structures shared across workflows and the unique characteristics of individual activities.
- Extension and Refinement of Entities, Relations, and Attributes
  - We examined aspects of archival workflows and visual arts practices that were difficult to represent using only the existing components of RiC-CM, and refined or extended the necessary entities, relations, and attributes. Definitions and application guidelines for the new components were established, and their suitability was assessed using actual data from the Jung Jungyeob Collection.
- Mapping the Core Workflow Models to RiC-CM and Defining New Entities and Relations
  - The core workflow models were mapped to the entities, relations, and attributes defined in RiC-CM. To represent the characteristics of archival workflows and visual arts practices that could not be adequately expressed using the existing standard, one new entity and nine new relations were defined.
  - Definitions and application guidelines for these new components were established, and their applicability was evaluated using actual data from the Jung Jungyeob Collection.
- New Entity

<table>
  <tr>
    <th width="180" align="center">Entity&nbsp;ID</th>
    <th width="160" align="center">Entity&nbsp;Name</th>
    <th width="180" align="center">Entity&nbsp;Type</th>
    <th width="500" align="center">Definition</th>
  </tr>
  <tr>
    <td align="center">RiC&#8209;E23</td>
    <td align="center">Artwork</td>
    <td align="center">Artwork</td>
    <td align="center">An identifiable individual artistic creation conceived or produced through artistic activity, distinguished from its physical or digital instantiations.</td>
  </tr>
</table>

- New Relations

<table>
  <tr>
    <th width="180" align="center">Relation&nbsp;ID</th>
    <th width="460" align="center">Relation&nbsp;Name</th>
    <th width="380" align="center">English&nbsp;Label</th>
  </tr>
  <tr>
    <td align="center">RiC&#8209;R087</td>
    <td align="center">has target</td>
    <td align="center">Targets</td>
  </tr>
  <tr>
    <td align="center">RiC&#8209;R088</td>
    <td align="center">organizes or organized</td>
    <td align="center">Plans, coordinates, and oversees operations</td>
  </tr>
  <tr>
    <td align="center">RiC&#8209;R089</td>
    <td align="center">enters or entered into agreement with</td>
    <td align="center">Enters into an agreement</td>
  </tr>
  <tr>
    <td align="center">RiC&#8209;R090</td>
    <td align="center">uses or used</td>
    <td align="center">Uses</td>
  </tr>
  <tr>
    <td align="center">RiC&#8209;R091</td>
    <td align="center">produces or produced</td>
    <td align="center">Produces</td>
  </tr>
  <tr>
    <td align="center">RiC&#8209;R092</td>
    <td align="center">requests or requested</td>
    <td align="center">Requests</td>
  </tr>
  <tr>
    <td align="center">RiC&#8209;R093</td>
    <td align="center">approves or approved</td>
    <td align="center">Approves</td>
  </tr>
  <tr>
    <td align="center">RiC&#8209;R094</td>
    <td align="center">originates or originated</td>
    <td align="center">Creates</td>
  </tr>
  <tr>
    <td align="center">RiC&#8209;R095</td>
    <td align="center">provides context for</td>
    <td align="center">Provides context</td>
  </tr>
</table>

## 4. Core Workflow Models of the Collection Visualization Beta

- Structure of the Core Workflow Models
  - Based on the analysis of entities and relations in existing collections, we categorized workflows such as acquisition, registration, management, and utilization, as well as relationships between artworks and art archival materials, into ten core models. Each model was developed based on a common structure comprising the agents responsible for each workflow, the objects involved, applicable regulations, and related records, with additional entities and relations reflecting the unique characteristics of individual activities. ※ The core workflow models include both activity-centered models focusing on acquisition, management, and utilization, and relationship-centered models focusing on artworks, art archival materials, and storage facilities.
  - The ten core models are organized into the following four categories:
    1\. Acquisition and Registration: Acquisition Activities, Acquisition Appraisal, Donation and Accessioning, and Registration
    2\. Management and Operations: Storage Facilities, Transfer of Administrative Responsibilities, and Management and Operations
    3\.- Access and Utilization: Exhibitions, Education, and Programs; Temporary Removal, Loans, and Public Access
    4\.- Artworks and Art Archival Materials: Artworks and Archival Materials

- Acquisition and Registration
  - Activities and relationships involved in the acquisition of collections.

![Core models for acquisition and registration](./images/image2.jpg)

- Management and Operations
  - Relationships involving storage facilities, transfers of administrative responsibilities between departments, and management activities.

![Core models for management and operations](./images/image3.jpg)

- Access and Utilization
  - Relationships related to collection research, utilization, and user services.

![Core models for access and utilization](./images/image4.jpg)

- Artworks and Art Archival Materials
  - Contextual relationships among artists, artworks, collections, and art archival materials.

<p align="center">
  <img src="./images/image5.jpg" alt="Relationships among artworks and art archival materials" width="500">
</p>

- Conversion and Visualization of RiC-CM Mapped Data into RiC-O
  - To visualize the RiC-CM mapped data as an ontology graph, the data must first be converted into RDF format using RiC-O. This is because the International Council on Archives (ICA) distributes a base RDF file that defines the structure and components of RiC-O.
  - Using the RiC-O annotation property rico:RiCCMCorrespondingComponent, we mapped the entities, attributes, and relations from RiC-CM to the corresponding RiC-O classes and properties (datatype properties and object properties). We then used Python's openpyxl library to read the Excel data and rdflib to convert it into RDF format. Finally, the resulting RDF data was imported into the ontology visualization tool GraphDB to visualize the relationships between entities.

## 5. Exploring the Collection Visualization Beta

- Applied Standards: RiC-CM (v1.0), RiC-O (v1.1)
- Target Collection: Jung Jungyeob Collection
  - [Access the Core Workflow Models Ontology Graph (Click) – Starting Node: Jung Jungyeob Collection](http://121.131.4.200:7200/graphs-visualizations)
    - Login is required to ensure a consistent operating environment. (Username: user / Password: semaaa)
    - If the graph does not display immediately, go to the left-hand menu and select Explore > Visual graph, then choose Jung Jungyeob Collection for each starting node under Saved graphs.
- Tool Used: Semantic graph database GraphDB
- Navigation Instructions: Interact with the graph using mouse controls
  - Click a node to view its detailed information.
  - Double-click a node or click the expand button that appears on mouseover to reveal additional nodes connected by relations, expanding the graph.
  - Click the focus button that appears on mouseover to re-center the graph around the selected node.
  - Relationship lines between nodes are labeled with the corresponding relation. When multiple relations exist, they are summarized for readability; click the line to view all associated relations.
    - You can identify the subject and object of each relation based on the reading direction of the text (e.g., subject → object).
  - Use the magnifying glass icon in the top-right corner to search for nodes.

![Ontology graph of the Jung Jungyeob Collection](./images/image6.jpg)

## 6. Significance of the Collection Visualization Beta

- Refinement of Workflow-Centered Relationship Structures
  - Building on the existing model that connected various types of collection-related information, we organized the relationships among responsible agents, objects, applicable regulations, and related records within each workflow. This approach makes it possible to understand the structure of individual workflows more clearly.
- Categorization of Core Workflow Models
  - We developed ten core workflow models, distinguishing common structures shared across multiple workflows from relationships unique to individual activities. These models provide a foundation for application to other collections.
- Extension of Entities and Relations for Art Archives
  - While utilizing the existing components of RiC-CM, we defined additional entities and relations needed to represent archival workflows and the characteristics of visual arts practices, and refined their application guidelines.
- Limitations and Future Directions
  - As this is a pilot model developed using the Jung Jungyeob Collection, further application to other collections and workflows is necessary to evaluate its validity. In addition, the readability of relationships and ease of navigation need to be assessed in an actual service environment, and methods for integrating the model with existing SeMA AA data should continue to be explored.

## Previous Research

- The Collection Visualization Beta, developed based on the Rim Dongsik Collection, can be accessed via the [SeMA AA GitHub account (Click)](https://github.com/SeMA-AA).

## Contact

- semaaa@seoul.go.kr
- 02-2124-7400

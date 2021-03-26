# Foodweb for agroecology

## Problem

An ecosystem characterizes an environment in which the physical chemical conditions are relatively homogeneous and allow the development of a set of living organisms. The ecosystem is thus the whole of a biotope (physical-chemical conditions of the environment) and a biocenosis (animal, plant, fungal,protozoan, protist) that interact with each other.

Within these ecosystems, there is a great diversity of interactions between living things. Examples include predation, competition, cooperation, symbiosis, parasitism, etc. These interactions form trophic relationships between species that can be modeled as networks  (a set of nodes  and links between these nodes).

![trophic networks](https://hack4nature.slite.com/api/files/EMSATFHpgL/ksdk.png "Trophic Network")

> The graph theory (©Styleshout and Thibault Liétard) and the representation of food web (©Vector illustration from Vecteezy)

Agricultural ecosystems are no exception. Indeed, in agrosystem the cycle of nutrients on which cultivated plants depend is under the influence of many trophic interactions. The stability  of the foodweb structure within the agrosystems  therefore  strongly  influence their agronomic performance and viability  in the long term.  However, agricultural practices  such as tillage, drainage, interculture, rotation, over-grazing and the intensive use of pesticides and fertilizers have a significant impact on wildlife species, which influences the structure  of the foodwebs. Thus, despite the fact that  the  diversity of living communities is  essential to the functioning of agricultural systems,it is sometimes  ignored by agronomists who focus mainly on physical and chemical factors.

Today, ecological modelling offers new opportunities to link food network models with agronomic models and create innovative frameworks. The use of graph theory thus allows information to be represented and linked to different intra- or interspecific interactions (between two/several individuals of the same species or between two/several individuals of different species).

## Projet idea

With this in mind, we would like to experiment with graph databases\* ( for example, property graph engine like Neo4j, RDF Engine like GraphDB, DGraph, Python RDFLib or advanced OWL / Knowledge Graph Engine like Grakn, TerminusDB), capable of managing many interconnected information and with a simplified query language(NoSQL) or SparQL.

This database should  be used to identify the interactions between different animal and plant species in agricultural systems. It should also help for identifying the missing species of the network and thus guide the choice of crops within the framework of  agroecological practices, which promote diversity on farms.

The identification, through biotic interactions, of companion species could thus go a long way in controlling pest species and limiting the use of pesticides in a long-term perspective.

![species interactions graph](https://hack4nature.slite.com/api/files/tT6dWrXncS/HB.png "Tspecies interactions graph")

> A graph database (GDB) is a database that uses graph structures for semantic queries with nodes, edges, and properties to represent and store data. A key concept of the system is the graph (or edge or relationship). The graph relates the data items in the store to a collection of nodes and edges, the edges representing the relationships between the nodes.

Network-Report
==============

## Conal McSweeney - IS30320 Network Report

The graph I have produced is a visual representation of my friends network on Facebook. I used an application named ‘Netvizz’ to extract the data I wanted from Facebook, which I would then use to produce my graph through Gephi. A .gdf file is required to import the Facebook data into Gephi, Netvizz gives us the option to download a .gdf file directly to a hard drive and from there it is a simple import command to start the graph project.

After the initial import of my Facebook data, my graph consisted of 176 nodes and 1876 edges. When the graph is first imported, there is no color, shape or distinctive features thus making information almost impossible to derive purely by looking at it. The graph represents an egocentric network as I am connected to all of the other vertices within. 

There are multiple algorithms available to modify your graph such as Fruchterman-Reingold and ForceAtlas2. These algorithms modify the shape of the data within the graph and allow the user more readability. I used the ForceAtlas2 algorithm to modify my graph. This algorithm forces the nodes to repel off one another and the edges attract the nodes, this provides a well-balanced spread of the data. The speed of which the graph morphs during this algorithm can be modified so I could control the shape and size of the graph that I wanted. If something goes wrong it must be done again from the beginning. 

The next option with the graph was statistics for which I chose the modularity option. According to the statistical report, my graph/network had a total of 11 communities within, some of these only contained on person so therefore it is really only around 5 or 6 larger communities. The different communities or social groups each have their own individual color. It can also be seen that the larger communities have far more nodes and edges that makes the entire group seem clustered together. These larger communities are groups of people in my life that I would be in almost constant contact with and would know many people from these social groups. Examples of these communities include secondary school, family, work, college etc. 

Following on from the modularity statistics option, I focused on the information that each single node provides. Betweenness centrality gives me an indicator of the importance and centrality of each node within the network. “Betweenness centrality is a measure of how often a given vertex lies on the shortest path between two other vertices.” (Hansen, D. L., Shneiderman, B., & Smith, M. A. (2011)). We can see these relationships almost like bridges, if we remove one vertex; we are potentially severing a connection to other nodes and changing the composition of the graph. 

From my attached graph we can see that within the different communities/groups there are multiple nodes that are larger and more prominent than others. The larger the nodes, the more connected they were to different people across the graph. To apply this information in terms of real life, the large nodes that connect two or more social communities in my graph could be people I was in secondary school with that now also attend the same college or are in the same course. 

To find out which of the nodes or friends were connected to most of the others I used the average degree statistics option. If I ranked the degree of the nodes by their size then the nodes with the most connections appear larger than the less connected nodes. 

The final visual representation of my graph shows each of the different social groups/communities in their own unique color that allows them to stand out. The strong and weak ties are shown through nodes that are clustered together and nodes that are singled out from the groups. ForceAtlas2 has helped to morph the communities into a visually aesthetic layout, which should be easy to read even for beginner Gephi users such as myself. 

The only feature I feel was lacking from the software was the ability to undo your actions if you make a mistake. Several times I had to start over if I had not saved recently. In conclusion, Gephi is a powerful and useful tool to display the Facebook data in such a vibrant visual form. The many statistic options allowed me to gain a greater understanding of the importance each individual node plays within the network including the concepts of bridging and betweenness centrality. 


*Word Count: 738*

- - -


#### References: 

Hansen, D. L., Shneiderman, B., & Smith, M. A. (2011). Analyzing social media networks with NodeXL: Insights from a connected world. Amsterdam: Elsevier, Morgan Kaufmann.

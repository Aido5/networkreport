Facebook - Network Report
=============
#####Question:Networks-Demonstrate your understanding of the following terms; Nodes, Edges, Influence, Bridging, Bonding, Degrees, and, Betweeness, Closeness and Eigen-vector centrality in relation to your graph.
---
Network analysis provides us with a visual representation of our interpersonal ties. For our assignment, we used Facebook, which is a multimodal network. To illustrate our data, we created a graph using Gephi, a visualisation platform. This report will outline some of the key concepts in data visualisation, while also providing a personal insight into how I created my own network graph. 
######Important Terms
In regards this assignment using *Gephi*, a node is one of my Facebook friends. These **nodes** are connected by a series of lines, known as **edges**. The degree of a node is the number of edges it has. These can be in or out relations. If a node (or friend) has a high degree, it means they have a lot of connections and neighbours. 

Two important concepts in network analysis are **bridging** and **bonding**. They both connect nodes, but in different ways. Bonding is the connection within a group or community of nodes. Bridging is the connection of a group or cluster to another. Within the context of a Facebook network, a person may be a bridger if they connect two clusters. To find a bridger, is it necessary to calculate *betweenness centrality*, which outlines how often one individual is likely to connect groups. High betweeness centrality would indicate a high amount of bridging. 

######How I created my graph
I am now going to discuss the process for creating a network graph using Gephi. The first step is to use a Facebook application called *netwizz* to download my data. Then, it was just a case of opening this information in *Gephi*, with the result being a chaotic cluster of nodes, representing my 484 friends. 

From here, I proceeded to filter my network, to make the data more manageable. I did this by going to the filter option, topography, degree range, then toggled the bar until I was satisfied with my network. I also went into my data laboratory, and manually deleted friends. To make the graph easier to read, I selected *“Force Atlas 2”* from the layout option, which spread all of the nodes out. To further enhance the clarity of the graph, I divided the clusters by colour. To do this, I ran the modularity option, and then selected “modularity class”, before clicking apply.

At this point, I was left with 20 nodes, 24 edges, and 4 clusters, all colour-coded. I then applied labels to all of the nodes, which indicated exactly the person that the node represented. In order to make the overall graph more readable, I changed the size of the labels. 
Visualisation clarity was the main objective of this exercise, and to achieve this, I manually moved nodes around. I left enough space so labels and clusters could be distinguished clearly. I also made sure that any bridgers stood out significantly. 
By clicking *“Preview”*, I brought up a visualisation of my Facebook network. I increased the weight of the edges, just to enhance the look of the graph. Once I was satisfied with the overall look, **I saved my graph in PDF format** and my network analysis was complete.

I found it intriguing to see how my friends were grouped together. My biggest community of course was from my hometown down the country, where I probably know the most people. Within my University friends, there was also a visible divide. One community comprised of my society friends, while the other community was made up of classmates.

I believe this is the core foundation of data visualisation: helping us see things that were not obvious before. I can see how a graph would save time and effort, compared to trawling through unorganised amounts of raw data. But most of all, graphs, such as those created using *Gephi*, are easy on the eye and help us recognise otherwise inconspicuous patterns. 


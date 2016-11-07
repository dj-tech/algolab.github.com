---title: Home
---

AlgoLab - Algorithms in Bioinformatics Lab
==========================================



--- 
project: [https://algolab.eu/]
--- 

---
title: Home
---

## no update
AlgoLab is a research group focused on designing, studying, analyzing and implementing efficient algorithms, mainly combinatorial algorithms, for computational problems. The group is associated with the CS Dept. of Univ. Milano-Bicocca, but includes members of neighboring universities and research groups.

While the focus is on Computer Science, we are an interdisciplinary group, without defined boundaries on the fields of application of the algorithms studied. We are especially interested into algorithms and data structure to manage massive datasets (Big Data), as trivial or brute-force algorithms can suffice on modest dataset. On the other hand Big Data require linear or sublinear time algorithms with very small space requirements — such as streaming algorithms and succint data structures — or parallel algorithm.

Some more specialized topics of interests are:

    Text algorithms and data structures. We study algorithms and data structures for indexing and querying huge text collections.
    Combinatorics on words. We study different notions of distance between words, with a focus on classical definitions such as the longest common subsequence and the shortest common supersequence.
    Algorithms on trees. We study combinatorial algorithms for tree comparison and phylogeny reconstruction from matrices that encode the set of characters that the leaves have (e.g. the perfect phylogeny problem).
    Graph algorithms. We study some notions of graph decompositions — such as modular decomposition — and graph-based clustering (consensus and correlation clustering).
    Connections between texts and graphs. Modeling text problems, such as the shortest superstring problem, as  graph problem is a powerful tool to develop new algorithms. All known genome assembler (a genome is essentially a very long string which must be reconstructed from a set of substrings) are built upon the notion of string graph or de Bruijn graph.
    Computational, approximation and fixed-parameter complexity. We study how different parameters determine whether a certain problem admits and efficient solution, while classical computational complexity focuses on a single parameter: the size of the instance.

We strive for a delicate balance between theoretical and experimental aspects, as we believe it is the only way that a research activity that can produce results useful outside academia. In fact, there are several algorithms that are efficient from a theoretical viewpoint (that is, polynomial time algorithm) but they do not have an efficient implementation, either because the algorithm engineering that is necessary to this purpose has not been done, or is impossible to do. On the other hand, there are some cases where exponential or super-polynomial time complexity result in implementations that are efficient in practice (such as the simplex algorithm).

Often efficient implementations stems form combinatorial properties of the instances that we want to solve, and it is hard to find a priori which properties can lead to fast implementations. An example is the Burrows-Wheeler Transform that is based on sorting all rotations of the text, has been introduced to compress texts but, a decade later, has shifted its main application in text indexing.
Recent Posts
Workshop on Graph Assembly Algorithms for omics data
October 26, 2016 by Gianluca Della Vedova, posted in Events	

November 18th, 2016 Univ. Milano-Bicocca. Building U24 – Room C02 Theme and scope New and different sequencing technologies have appeared in the last few years with the promise of overcoming Illumina as the reference platform: PacBio, 10x Genomics, and MinION being the most relevant today. Those technological improvements have shown the limitations of managing linear … Continue reading Workshop on Graph Assembly Algorithms for omics data
Tesi: Algoritmi per l’assemblaggio di multiple stringhe di DNA
July 18, 2016 by simonezaccaria, posted in Stage	

Descrizione Le recenti tecnologie di sequenziamento sono in grado di produrre un’ampia quantità di piccoli frammenti di DNA. Tuttavia, la complessità del genoma, tra cui le enormi dimensioni e le diffuse variazioni, rende necessario il disegno di algoritmi avanzati per l’assemblaggio dei frammenti finalizzato alla sua ricostruzione (necessaria per le importanti applicazioni in campo medico). … Continue reading Tesi: Algoritmi per l’assemblaggio di multiple stringhe di DNA
Tesi: Euristiche applicate all’assemblaggio di aplotipi
July 18, 2016 by simonezaccaria, posted in Stage	

Descrizione Le recenti tecnologie di sequenziamento sono in grado di produrre un’ampia quantità di piccoli frammenti di DNA. Tuttavia, la complessità del genoma, tra cui le enormi dimensioni e le diffuse variazioni, rende necessario il disegno di algoritmi avanzati per l’assemblaggio dei frammenti finalizzato alla sua ricostruzione (necessaria per le importanti applicazioni in campo medico). … Continue reading Tesi: Euristiche applicate all’assemblaggio di aplotipi
Tesi: Algoritmi di indicizzazione del grafo del pangenoma
April 28, 2016 by Gianluca Della Vedova, posted in Stage	

Descrizione La tesi si occupa di modellare, disegnare e implementare nuovi metodi di pattern matching dove il testo non è più una struttura lineare, ma è rappresentabile da un grafo orientato aciclico dove i vertici corrispondono a porzioni di genoma condivisi da uno o più individui e gli archi identificano le varianti genomiche presenti in … Continue reading Tesi: Algoritmi di indicizzazione del grafo del pangenoma


# Can an Unsupervised Temporal Analysis Provide Useful Magic: The Gathering Data
Masters Capstone Project. 

Full paper available in "Capstone_project(5)(1).pdf" file.


                                                          Abstract
In Magic: The Gathering the key to a good analysis of the game is the constant analysis of tournament winning results. These results feature human labelled categories and may fall victim to human labelling bias. Within the scope of this project the aim is to tackle a temporal analysis of Magic: The Gathering Standard format, through the lens of an unsupervised community detection algorithm. The results show that this approach is capable of detecting strong, clear and meaningful partitions, that can further be used to analyse the health of the Magic: The Gathering game without the use of human labels.



                                                          Acknowledgment
I would like to thank Dr. Patrick Mannion for supervising and supporting this project.

                                                          Main Research Questions 
The main research questions that will be answered through this project are;
1) Is an unlabelled clustering approach a viable way of assessing the current state of a format and by extension a viable way of preforming a temporal analysis?
2) Can the data provided by a temporal analysis this way provide feedback to designers free from human bias?
3) Can this Framework be applied to other formats and CCGs?

                                                          Documents in Repository 
CapstoneProject.ipynb -- was used as the main coding file where all the main pipelines exist to compile and display data.

cLouvainTest.ipynb -- is the file used to test concensus clustering on the louvain algorithm and to find the optimal parameters for it.

Capstone_Project.pdf -- is the IEEE styled pdf document used as the final submission.

Additional_Documentation.pdf -- is a couple more examples of tracking communities over time, mainly a clean showcase of all the Jaccard similarity tables.

The accompanying pngs used within the main document are also present;
+ Modularity.png - the modularity of the graphs over time.
+ Number of Communities.png - the number of communities over time.
+ Normalised Shannon index.png - the Pielou's evenness index over time.
+ PageRank-bans3.png - the PageRank scores for the banned cards graphed.
+ Normalised Card Occurrences-bans3.png - the Normalised Card Occurrences scores for the banned cards graphed.
+ PageRank-comp3.png - both banned and unbanned card's PageRank scores for comparison.
+ Normalised Card Occurrences-comp3.png -both banned and unbanned card's Normalised Card Occurrences scores for comparison.


                                                          References 
[1] G. N. Yannakakis and J. Togelius, Artificial Intelligence and Games, 2nd ed. Springer Nature, 2025. https://gameaibook.org

[2] C. Alvin, M. Bowling, S. Rivers-Green, D. Siglin, and L. Alvin, “Toward a Competitive Agent Framework for Magic: The Gathering,” The International FLAIRS Conference Proceedings, vol.34, 2021.

[3] S. Fortunato and D. Hric, “Community detection in networks: A user guide,” Physics Reports, vol. 659, pp. 1–44, 2016.

[4] M. E. J. Newman, “Modularity and community structure in networks” Proc. Natl. Acad. Sci., vol. 103, no.23, pp. 8577–8582, 2006.

[5] S. Fortunato and M. Barthel´emy, “Resolution limit in community detection,” Proc. Natl. Acad. Sci., vol. 104, no. 1, pp. 36–41, 2007.

[6] V. D. Blonder, J.-L. Guillaume, R. Lambiotte, and E. Lefebvre, “Fast unfolding of communities in large networks,” J. Stat. Mech. Theory Exp., vol. 2008, no. 10, p. P10008, 2008.

[7] A. Lancichinetti and S. Fortunato, “Consensus clustering in complex networks,” Scientific Reports, wol. 2, Art. no. 336, pp. 1–7, 2012.

[8] L. Danon, A. D´ ıaz-Guilera, J. Duch, and A. Arenas, “comparing community structure identification” J. Stat. Mech. Theory Exp., no. 9, pp. 219–228, 2005.

[9] L. Hubert and P. Arabie, “Comparing partitions,” J. Classif., vol. 2, no. 1, pp. 193–218, 1985.

[10] C. E. Shannon, “A mathematical theory of communication,” Bell Syst. Tech. J., vol. 27, no. 3, pp. 379–423, 1948.

[11] L. Jost, “The relation between evenness and diversity,” Diversity, vol. 2, no. 2, pp. 207–232, 2010.

[12] S. Brin and L. Page, “The anatomy of a large-scale hypertextual Web search engine,”Comput. Networks ISDN Syst., vol. 30, pp. 107–117, 1998.

[13] MTGTop8, Magic: The Gathering Decklists Database, [Online]. Available: https://mtgtop8.com/index

[14] Scryfall, Oracle Cards Bulk Data dataset version oracle-cards20260508090243, May 8, 2026. https://scryfall.com/docs/api/bulk-dat
 

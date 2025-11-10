Name: Chia-Lun Tsao
Email: ctsao@ucsd.edu
Section: B06
Mentors: Alex Cloninger, Rayan Saab

The most interesting topic in our group this quarter was the topic on statistical optimal transport. Throughout the first few weeks, we realized that there were close connections between optimal transport and statistics, and we could use this intersection in enhancing our understanding of how optimal transport works in data science in a more statistical point of view. This brought new perspectives for us to understand different types of data and we could relate that to our quarter 2 project.

One potential problem that our group is willing to investigate is related to the computational aspect of optimal transport on (near) isotropic distributions. In the paper written by Max Kuand and Esteban Tabak, they were investigating the effects of standardizing on point clouds and how that would effect the computational aspect of optimal transport. They found that that for point clouds having the same first two moments, the computation of optimal transport will have much better accuracy by testing on datasets empircally. However, there is little theory behind why this is generally true. Therefore 

We think that some of the methodologies in the original papar could have been improved in terms of the data fidelity and how to implement the respecting optimal transport algorithm. For example, the plant data that the paper originally covered only contained plant data of tomatoes and maize for two days, which we consider insufficient for the analyais of point clouds using optimal transport. Therefore, we would like to use another dataset which has more point cloud data to implement our linear optimal transport analysis on it rather than the original data in the paper.

For our project, we would also like to try other methods from optimal tranpsort that were brought up by our mentors: In particular, the original result simply used the vanilla optimal transport methods. Recently, however, our mentors have written a paper which uses a linear optimal tranpsort framework, of which we can conduct common machine learning practices in the embedding space after we mapped the data. Therefore, we would like to try this out and see if there is a difference compared with the original plant data that we are investigating.



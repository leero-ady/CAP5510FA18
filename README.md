## CAP5510 - Bioinformatics Project Proposal


### Project Title
Protein Secondary Structure Prediction with Long Short Term Memory Networks

### Team Members
Aditya Nalluri UFID: 64153915\
Sai Madhav Kasam UFID: 17351683

### Abstract:
Prediction of protein secondary structure from the amino acid sequence is a classical bioinformatics problem.
Common methods use feed forward neural networks or SVM’s combined with a sliding window, as these models
does not naturally handle sequential data. Recurrent neural networks are an generalization of the feed forward
neural network that naturally handle sequential data. We use a bidirectional recurrent neural network with long
short term memory cells for prediction of secondary structure and evaluate using the Protein Data Bank dataset.


### Plan of action:
- In the project, six proteins that belongs to different secondary categories would be considered.  
- Primary amino acid codes of these proteins from protein data bank will be collected.
- Encode each primary sequence and DSSP codes. 
- Train the neural network using encoded codes.
- The secondary structure of these proteins is evaluated based on the tendencies of the amino acids to form different secondary structures.   
- The DSSP codes of the proteins will be fed as inputs for the classifier to classify the proteins into the basic tertiary topologies.



### Work load:
The work load will be divided among all of us equally and three of us will participate in all aspects of the project . 

### References:
[1] Bordoloi H., Sarma K.K. (2012) Protein Structure Prediction Using Multiple Artificial Neural Network Classifier. In: Patnaik S., Yang YM. (eds) Soft Computing Techniques in Vision Science. Studies in Computational Intelligence, vol 395. Springer, Berlin, Heidelberg.\
Protein secondary structure prediction with long short term memory networks
[2] SØNDERBY, S. K., AND WINTHER, O. Protein secondary structure prediction with long short
term memory networks. arXiv preprint arXiv:1412.7828 (2014).

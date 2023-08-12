# Facial Verification using Siamese Network
The Facial Verification using Siamese Network project aimed to develop an accurate and efficient system for facial recognition. This system utilized a Siamese network architecture, a type of neural network designed to compare and identify similarities between two input images. The primary objective was to determine whether a given test image matched the positive images in the database.

The Siamese network architecture consists of two identical subnetworks that share weights and parameters. These subnetworks take in pairs of images as input and generate embeddings, which are numerical representations of the images' features. The embeddings are then compared using a distance metric, often Euclidean distance or cosine similarity. If the distance between the embeddings of the test image and a positive image is below a certain threshold, the system classifies the test image as a match to the positive image.

To train the Siamese network, a dataset of pairs of images was collected. Each pair contained a positive image pair (images of the same person) and a negative image pair (images of different people). The network learned to minimize the distance between embeddings of positive image pairs and maximize the distance between embeddings of negative image pairs.

During testing, the trained network was given a test image and compared its embedding with embeddings of positive images in the database. If the distance was below the threshold, the system classified the test image as a match. This approach proved effective for facial verification tasks, even in scenarios with variations in lighting and facial expressions.

Overall, the Facial Verification using Siamese Network project successfully demonstrated the capability of Siamese networks in accurately identifying whether a given test image matches the positive images in the database, offering a robust solution for face recognition tasks with improved accuracy and generalization.

### DATASET
[Labelled Faces in the Wild Dataset (Tar GZ - 173MB)](http://vis-www.cs.umass.edu/lfw/#download)

### PAPER
[Siamese Neural Networks for One-shot Image Recognition](https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf)

### LICENSE
[MIT LICENSE](LICENSE)

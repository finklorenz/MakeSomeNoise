# Manufacturing_Sound_Classification

This is the code for our contribution to the 10th CIRP Conference on Assembly Technology and Systems (CIRP CATS).

### Citation:
If you use (parts of) this code, please cite our paper: LINK-TDB

CITATION-TBD

## Abstract:
With 32 million people working in the European manufacturing sector, human work still plays a crucial role in industry. However, due to lot size one manufacturing and increased quality requirements, the complexity of products and processes is growing. Therefore, numerous approaches introduce adaptive assistance systems in assembly to support workers during complex work tasks and adapt their level of assistance to the current situation. To enable adaptivity, human action recognition must be incorporated into the consideration of context. Until now, research has focused on providing context to the machine through wearable sensors or cameras. However, wearable sensors hinder worker’s movements and cameras have difficulties distinguishing between work steps of high visual similarity. To mitigate these challenges, we present a new method to classify manual work steps only by their typical acoustic characteristics. The proposed method uses log-Mel spectrograms of work sounds fed into a convolutional neural network (CNN), thus learning their characteristic structure and providing context to the machine. The CNN was inspired by the VGG-13 architecture; with four convolutional blocks and a fully connected layer, enhanced by a frequency normalisation layer. Moreover, we present a new public dataset for the acoustic classification of manual work steps. The dataset includes typical sources of sounds in manufacturing, e.g., bench grinder, cordless screwdriver, drill press, filing, grabbing screws, hammering, or sanding. Before feeding the data to the CNN, we apply various pre-processing and data augmentation techniques to increase generalization capabilities. Our method can detect work steps with reliable accuracy, proving that detecting work context through acoustics is possible and feasible, thus enabling differentiation of visually similar work steps.

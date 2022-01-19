# Unipose-COCO

## ECE 285 Final Project with Gokulakrishnan Candassamy

## We implement the UniPose Architecture by Artacho and Savakis on the COCO dataset

# Abstract
Artacho and Savakis [1] proposed the UniPose architecture in 2020 which achieved
state-of-the-art results for 2D pose estimation in images. In our paper, we implement this architecture starting from scratch and evaluate its performance on the
COCO (Common Objects in Context) datatset [2] while making use of the results
corresponding to the MPII dataset by Artacho and Savakis as a benchmark. We also
experimented with hyper-parameters, dataset size, and used pre-trained weights as
part of experimentation to find the optimum performance of the UniPose architecture on the very challenging keypoints detection benchmark dataset, COCO. Our
results reveal that the COCO dataset is a much larger dataset with more variation
than that of the MPII and thus requires more time to train to match the accuracy of
that of MPII. However, the UniPose architecture itself learns from this dataset with
decrease loss with the optimal parameters leading to the highest accuracy being
with a batch size of 16, weight decay of 0.005, the entire dataset, and >100 epochs.

## Citations
[1] Bruno Artacho and Andreas Savakis. Unipose: Unified human pose estimation in single images
and videos. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition
(CVPR), June 2020.
[2] Tsung-Yi Lin, Michael Maire, Serge Belongie, Lubomir Bourdev, Ross Girshick, James Hays,
Pietro Perona, Deva Ramanan, C. Lawrence Zitnick, and Piotr Dollár. Microsoft coco: Common objects in context, 2014. cite arxiv:1405.0312Comment: 1) updated annotation pipeline
description and figures; 2) added new section describing datasets splits; 3) updated author list.

# MultiSectionCNN
Code for the paper "A Lightweight Multi-Section CNN for Lung Nodule Classification and Malignancy Estimation"
<a href=https://www.researchgate.net/publication/328774789_A_Lightweight_Multi-Section_CNN_for_Lung_Nodule_Classification_and_Malignancy_Estimation>
  Paper Link
</a>


Network Architecture
--------------------

<p align="center">
  <img src="pipeline.png" width="640" height="330" />
</p>


# Training
Code for generating the cross sections is shared in the notebook <br>
Stage 1 training is done by doing transfer learning using all the generated cross-sections. <br>
Stage 2 training is done on the maxpooled features for each cross-section. <br>

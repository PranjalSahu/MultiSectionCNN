# MultiSectionCNN
Code for the paper "A Lightweight Multi-Section CNN for Lung Nodule Classification and Malignancy Estimation"


Network Architecture
--------------------

<p align="center">
  <img src="pipeline.png" width="640" height="330" />
</p>


# Training
Code for generating the cross sections is shared in the notebook <br>
Stage 1 training is done by doing transfer learning using all the generated cross-sections. <br>
Stage 2 training is done on the maxpooled features for each cross-section. <br>

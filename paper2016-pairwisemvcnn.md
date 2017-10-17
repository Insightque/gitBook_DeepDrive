| 논문명 | Pairwise Decomposition of Image Sequences for Active Multi-View Recognition |
| --- | --- |
| 저자\(소속\) | Edward Johns (Imperial College London, UK) |
| 학회/년도 | May 2016, [논문](https://arxiv.org/abs/1605.08359) |
| 키워드 |  |
| 데이터셋(센서)/모델 |  |
| 참고 |[CVPR2016](https://www.youtube.com/watch?v=7Bw0HGlidtg)  |
| 코드 |  |


# Pairwise MVCNN

We propose to bring Convolutional Neural Networks to generic multi-view recognition, by 
- decomposing an image sequence into a set of image pairs, 
- classifying each pair independently, and 
- then learning an object classifier by weighting the contribution of each pair

제안 방식의 장점 : This allows for recognition over arbitrary(임의) camera trajectories(궤도), without requiring explicit training over the potentially infinite number of camera paths and lengths. 

Building these pairwise relationships then naturally extends to the **next-best-view problem** in an active recognition framework. 
- To achieve this, we train a second Convolutional Neural Network to map directly from an observed image to next viewpoint.

Finally, we incorporate this into a trajectory optimisation task, whereby the best recognition confidence is sought for
a given trajectory length.

## 1. Introduction

![](https://i.imgur.com/hsqKgpl.png)
```
[Figure 1]
- We propose a method for multi-view object recognition, by decomposing an image sequence into a set of image pairs. 
- Training on these pairs then allows for recognition and trajectory planning, without the need to train directly over the infinite possible number of camera paths that may exist.
```
Consider the scenario in Figure 1. What trajectory
should the camera move around the object in order to
achieve the highest recognition confidence in a given time?


<!--stackedit_data:
eyJoaXN0b3J5IjpbNDYxMTUyNTI0XX0=
-->
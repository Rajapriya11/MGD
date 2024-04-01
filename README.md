# Automated Mebomian gland segmentation


         ![image](https://github.com/Rajapriya11/MGD/assets/119552816/96fdbf45-e38a-4fdc-aec6-bd4231cd3a4f)




Dry eye disease, primarily caused by Meibomian gland dysfunction (MGD), is a significant global health concern. Ophthalmologists are increasingly focusing on MGD, particularly its severity and variations in Meibomian glands. But finding these glands in medical images is hard because they are distinct in appearance and they look similar to the nearby tissues. This project analyses the application of four deep learning-based segmentation algorithms to efficiently and precisely locate the Meibomian glands in meibography images. The performance of established models of Yolov8, U-Net, DeepLabv3+, and SegNet were compared. Out of these four models U-Net emerges as the most effective model, achieving 74.93% accuracy. U-Net was implemented with sigmoid activation function at the output layer and binary cross-entropy for binary classification.


Source dataset: https://mgd1k.github.io/index.html


Sample output : Meibomian gland segmentation of Yolov8 of this project

![image](https://github.com/Rajapriya11/MGD/assets/119552816/e762d4f7-9961-4f7e-ac4d-23a7d8a03740)

Predicted image of YOLOV8:

![image](https://github.com/Rajapriya11/MGD/assets/119552816/bb1124d1-95c2-4143-868a-30295ee7f1ca)


Sample data augmentation image of this project:

![image](https://github.com/Rajapriya11/MGD/assets/119552816/7eed35d4-1dad-414d-8a02-b1b0d5813486)


U-Net sample output: predicted U-Net mask

![image](https://github.com/Rajapriya11/MGD/assets/119552816/73f98384-2164-42ae-8d9e-f41eec2e058b)

Ground truth:


![image](https://github.com/Rajapriya11/MGD/assets/119552816/9723c567-cf3a-4646-84d0-783b57037bb5)


Original image:


![image](https://github.com/Rajapriya11/MGD/assets/119552816/5c356df6-29af-44bb-bb41-c21e1fb50be6)






# LifeVsion
Computer Vision in Healthcare

In recent years, telesurgery has experienced rapid development, numerous telesurgery applications in diverse areas have been reported. Among all telesurgery related components, computer vision (CV) is treated as one of the must have technologies, because it allows users to observe remote scenarios. In addition, a CV can further help the user to identify and track the desired targets from complex scenes. It has been proven that efficient CV methods can significantly improve surgery accuracy and relieve the user's physical and mental fatigue.
Hence, we decided to mimic this thought in our project and introduce Computer vision in telesurgery.

LifeVsion is based upon computer Vision technology. That could enhance the experience of a surgeon. Now definitely this question arises in everyone’s mind.

## What LifeVsion can perform?
1. Live streaming camera feed:
As telesurgery is a surgical procedure in which doctors perform surgery on a remote basis, hence it becomes necessary to provide real-time detection to the doctors.

2. Surgical instruments detection:
LifeVsion is based on computer vision technology, It is trained for detecting surgical instruments for the robotic arm to appropriately choose the right instruments during the surgical practice.
(here the idea is robots could figure out which instruments it need by detecting it and can switch it surgical instruments easily. We tried to mimic this idea on small scale by detecting small quantity of explicitly choosen surgeical instruments).

3. Augmenting the detected object information during live detection:
Here lifeVsion is equipped with another capability of displaying small information about the detected object using the Ideology of Augmented Reality which is generally used in Game development(Like: PokemonGo). In our model we augmented 2D image consist of message written explicitly over the detected object by simply using the coordinates of the detected object bounding box.

Model Training results:

![image](https://github.com/Mutyam3/LifeVsion-main/blob/main/assets/Detection01.png)

![image](https://github.com/Mutyam3/LifeVsion-main/blob/main/assets/Detection02.png)


Deployment of LifeVsion output video:
[Screencast from 2023-05-14 23-40-51.webm](https://github.com/Mutyam3/LifeVsion-main/blob/main/assets/LiveVision-Video.webm)

# Genetic-Algorithm

in this project,we will be creating a genetic algorithm which helps the
cars complete all the checkpoints in the track given below:
![image](https://github.com/muhammad-12345/Genetic-Algorithm/assets/111753966/27a54d5b-961e-4c61-bd61-7139794dd6b5)

The cars work by 5 sensors attached to it (left, top left, top, top right, right). If any one of these
sensors gets too close to a wall, it will turn on (Value = 1). Otherwise, it will stay off (Value = 0).
The car’s speed and rotation is fixed. It has 4 possible movement values (1, 2, 3, 4) where each value
represents that the car should move either forward, backward, left or right.
Each car has a chromosome attached to it. This chromosome is represented as a dictionary with
sensor combinations as keys and its respective movement as values.

In every generation, 30 cars try to cover the track (Stored in cars list).
The more checkpoints a car covers, the higher its score will be.
If a car collides with a wall, it will disappear.
If there are no cars left or the time has expired, it will begin preparations for the next generation.

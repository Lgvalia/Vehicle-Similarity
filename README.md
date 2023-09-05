# Repo for same ehicle similarity detection from different angles

In this repo you can find two techniques of image similarity detection, both from cv2 library - SIFT and ORB.

The idea of the project is to find same vehicles in different images, but if the images are taken from different angles of the vehicles.
The images of toy cars are used.

First I use SIFT technique to find keypoints and descriptors of the vehicles and then compare those with Brute Force matching. SIFT in this case does not provide promising output, as it fails to find similarities:
![Screenshot 2023-09-05 11 57 10 PM](https://github.com/Lgvalia/Vehicle-Similarity/assets/63636976/73ab40f5-b292-4111-8eaf-17a668fa7f63)

Another method that I use is ORB. Same Brute Force matching is used to compare keypoints and descriptors of two image of the same toy vehicle. In this case it is able to find some similarities, especially in markings of the vehicle:
![Screenshot 2023-09-05 11 59 39 PM](https://github.com/Lgvalia/Vehicle-Similarity/assets/63636976/d2665c90-b93e-41e6-b3bc-b5994fb19f54)

Either way none of the techniques deemed to be sufficient enough to use in real life situations, but still as a toy project on toy cars, it shows some promising aspects of the techniques used, especially this problem is quite difficult even for the human eyes to solve.


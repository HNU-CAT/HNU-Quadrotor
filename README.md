
# HNU-Quadrotor


<figure>
    <img src="./figs/cover.png" width="600">
    <figcaption>Three drones flying in the wild</figcaption>
</figure>


<figure>
    <img src="./figs/cover2.jpg" width="600">
    <figcaption>Design of the first generation of drones</figcaption>
</figure>

<figure>
    <img src="./figs/DSC00054.JPG" width="600">
    <figcaption>>Four drones flying indoors</figcaption>
</figure>


**Author：**[WHDworld](https://github.com/WHDworld), [XXLiu-HNU](https://github.com/XXLiu-HNU)

## Provided Materials

We provide the following resources:

* Editable drafts and assemblies [./hardware](./hardware)

| Caption               | Image Display                |
|-----------------------|------------------------------|
| UAV complete machine          | <img src="./figs/hnu-quadrotor.png" width="300"> |
| Battery compartment   | <img src="./figs/Battery compartment.png" width="300"> |
| Top view              | <img src="./figs/top.png" width="300">               |
| Mounting plate        | <img src="./figs/Mounting Plate.png" width="300">    |
| LiDAR installation        | <img src="./figs/lidar.jpg" width="300">    |

## Hardware Breakdown

The hardware structure is illustrated below:

![](./figs/hardware.png)
![](./figs/hardware2.png)


![](./figs/gif.gif)
## Bill of Materials


| Name                 | Type                          |
| -------------------- | ----------------------------- |
| LiDAR                | Livox MID360                  |
| Depth Camera         | Realsense D435i              |
| Onboard Computer     | Orin NX                   |
| Motor                | T-Motor F60 Pro KV1750            |
| Propeller            |  GEMFAN 5043                      |
| ESC                  | Micro Air  4 in 1   50A    |
| Battery              | DualSky 3300mAh 6S XP-3300HED |
| Flight Controller    | NxtPx4 v2                       |
| RC                   | Radiolink AT9S                |
| Receiver             | Radiolink R12DSM              |

## Use NUC as Onboard Computer
If you want to use the NUC as an onboard computer, you only need to install an additional top plate.

![](./figs/NUC.jpg)

## Optional sensor

To enhance flight stability and safety, especially in complex environments, we support the integration of additional sensors.

Optical Flow Sensor
We highly recommend adding an Optical Flow Sensor (e.g.,MTF-01) to the bottom of the airframe.

Safety Backup: In scenarios where primary positioning (GPS or LiDAR-SLAM) is lost or degrades, the optical flow sensor provides high-frequency velocity feedback.

Fly-away Prevention: This ensures the drone can maintain a stable hover and prevents the aircraft from drifting or "flying away" due to state estimation failure.

<img width="597" alt="Optional sensor layout" src="https://github.com/user-attachments/assets/07b2126a-7ae3-4f26-aac2-de5a010a9963" />


## Acknowledgments

When designing, we referred to the [super-hardware](https://github.com/hku-mars/SUPER-Hardware), [UniQuad](https://github.com/HKUST-Aerial-Robotics/UniQuad), [Fast-Drone-250](https://github.com/ZJU-FAST-Lab/Fast-Drone-250) projects and would like to express our sincere gratitude for this.

Gratitude to all contributors: Huidong Wang, Xingxun  Liu, Shaojie Li.

## Contact Us

If you have any questions about hardware or any other questions you want to consult, please contact us: liuxingxun@hnu.edu.cn

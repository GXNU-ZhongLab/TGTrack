# Top-down Cross-modal Guidance for Robust RGB-T Tracking (TGTrack)

The official implementation for the **TCSVT 2024** paper [Top-down Cross-modal Guidance for Robust RGB-T Tracking](https://ieeexplore.ieee.org/document/10614652)

<p align="center">
  <img width="50%" src="assets/pic-01.png" alt="Current RGB-T trackers vs our TGTrack"/>
</p>

This paper presents a Top-down Cross-modal Guidance mechanism to address the problem of weak discriminative power in target features learned due to the reliance on bottom-up attention in most current trackers. And a updater is proposed to help the tracker better update target features.

## Pipeline

![image](assets/pic-02.png)



## Resuts on LasHeR, RGBT234 and RGBT210

![image](assets/pic-04.png)

## Visualization


<p align="center">
  <img width="80%" src="assets/pic-03.png"/>
</p>

<p align="center">
  <img width="60%" src="assets/pic-05.png"/>
</p>

## Citation: 
```
@article{chen2024top,
  title={Top-down Cross-modal Guidance for Robust RGB-T Tracking},
  author={Chen, Liang and Zhong, Bineng and Liang, Qihua and Zheng, Yaozong and Mo, Zhiyi and Song, Shuxiang},
  journal={IEEE Transactions on Circuits and Systems for Video Technology},
  year={2024},
  publisher={IEEE}
}
```

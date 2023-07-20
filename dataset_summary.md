# A summary of large-scale collaborative perception datasets



| **Dataset**      | **Venue** | **Source** | **Frame** | **V2V**  | **V2I**  | **Agents** | **Camera** | **LiDAR** | **Depth** | **OD**    | **SS**    | **OT**    | **MP**    | **Website**                                          |
|:----------------:|:---------:|:----------:|:---------:|:--------:|:--------:|:----------:|:----------:|:---------:|:---------:|:---------:|:---------:|:---------:|:---------:|:----------------------------------------------------:|
| V2V-Sim [1]      | ECCV'20   | Simu       | 51K       | &#10004; | -        | 1-7        | -          | &#10004;  | -         | &#10004;  | -         | -         |  &#10004; | -                                                    |
| V2X-Sim [2]      | RAL'21    | Simu       | 10k       | &#10004; | &#10004; | 1-5        | &#10004;   | &#10004;  | &#10004;  | &#10004;  |  &#10004; |  &#10004; | -         | [Link](https://ai4ce.github.io/V2X-Sim)              |
| OPV2V [3]        | ICRA'22   | Simu       | 11K       | &#10004; | -        | 1-7        | &#10004;   | &#10004;  | -         | &#10004;  |  &#10004; | -         | -         | [Link](https://mobility-lab.seas.ucla.edu/opv2v)     |
| DAIR-V2X-C [4]   | CVPR'22   | Real       | 39k       | -        | &#10004; | 2          | &#10004;   | &#10004;  | -         |  &#10004; | -         | -         | -         | [Link](https://thudair.baai.ac.cn/coop-dtest)        |
| V2XSet [5]       | ECCV'22   | Simu       | 11K       | &#10004; | &#10004; | 2-5        | &#10004;   | &#10004;  | -         |  &#10004; | -         | -         | -         | [Link](https://github.com/DerrickXuNu/v2x-vit)       |
| DOLPHINS [6]     | ACCV'22   | Simu       | 42k       | &#10004; | &#10004; | 3          | &#10004;   | &#10004;  | -         |  &#10004; | -         | -         | -         | [Link](https://dolphins-dataset.net)                 |
| V2V4Real [7]     | CVPR'23   | Real       | 20K       | &#10004; | -        | 2          | &#10004;   | &#10004;  | -         |  &#10004; | -         |  &#10004; | -         | [Link](https://mobility-lab.seas.ucla.edu/v2v4real/) |
| V2X-Seq [8]      | CVPR'23   | Real       | 15k       | -        | &#10004; | 2          | &#10004;   | &#10004;  | -         |  &#10004; | -         |  &#10004; |  &#10004; | [Link](https://thudair.baai.ac.cn/coop-forecast)     |
| DeepAccident [9] | arXiv'23  | Simu       | 57K       | &#10004; | &#10004; | 1-5        | &#10004;   | &#10004;  | -         |  &#10004; |  &#10004; |  &#10004; |  &#10004; | [Link](https://deepaccident.github.io/index.html)    |

Notes
- Source: simulator (Simu) and real-world (Real).
- Frame refers to annotated LiDAR-based cooperative perception frame number.
- Supported common perception tasks: 3D object detection (OD), BEV semantic segmentation (SS), 3D object tracking (OT), motion prediction (MP).
    

References

1. [V2VNet: Vehicle-to-Vehicle Communication for Joint Perception and Prediction](https://arxiv.org/abs/2008.07519)
2. [V2X-Sim: Multi-Agent Collaborative Perception Dataset and Benchmark for Autonomous Driving](https://arxiv.org/abs/2202.08449)
3. [OPV2V: An open benchmark dataset and fusion pipeline for perception with vehicle-to-vehicle communication](https://arxiv.org/abs/2109.07644)
4. [DAIR-V2X: A Large-Scale Dataset for Vehicle-Infrastructure Cooperative 3D Object Detection](https://arxiv.org/abs/2204.05575)
5. [V2X-ViT: Vehicle-to-everything cooperative perception with vision transformer](https://arxiv.org/abs/2203.10638)
6. [DOLPHINS: Dataset for Collaborative Perception enabled Harmonious and Interconnected Self-driving](https://arxiv.org/abs/2207.07609)
7. [V2V4Real: A Real-world Large-scale Dataset for Vehicle-to-Vehicle Cooperative Perception](https://arxiv.org/abs/2303.07601)
8. [V2X-Seq: A large-scale sequential dataset for vehicle-infrastructure cooperative perception and forecasting](https://arxiv.org/abs/2305.05938)
9. [DeepAccident: A Motion and Accident Prediction Benchmark for V2X Autonomous Driving](https://arxiv.org/abs/2304.01168)
   
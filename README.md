# Know Where You’re Uncertain When Planning with Multimodal Foundation Models: A Formal Framework

The website of our paper "Know Where You’re Uncertain When Planning with Multimodal Foundation Models: A Formal Framework".

[[Project Page]](https://tinyurl.com/uncertainty-disentanglement) | [[Paper]](https://arxiv.org/pdf/2411.01639) | [[Arxiv]](https://arxiv.org/abs/2411.01639)

## Framework

<img src="docs/static/images/active_sensing.png" alt="Framework: Active Sensing" width="800">
<img src="docs/static/images/automated_refinement.png" alt="Framework: Automated Refinement" width="800">

We presented a novel framework for enhancing multimodal foundation models in robotic planning by disentangling, quantifying, and addressing perception and decision uncertainties. By isolating perception uncertainty in visual interpretation and decision uncertainty in plan generation, our approach enables targeted uncertainty management.

## Setup
```bash
$ pip install openai==1.40.2
$ pip install openai-clip==1.0.1
$ pip install seaborn
$ pip install pandas
$ pip install torch==2.2.2
$ pip install torchvision==0.17.2
```

## Example Notebooks
1. Disentangling and quantifying perception and decision uncertainty [here](uncertainty-quantification.ipynb).
2. Inference on our fine-tuned multimodal foundation model and comparison with benchmark [here](fine-tuned-model-inference.ipynb).

## Model Checkpoints
All model checkpoints are available on huggingface [here](https://huggingface.co/anonymous-yyh-1971).

## Datasets
### Calibration
1. [Carla Images](https://drive.google.com/drive/folders/1Nqp6psvKPDkaTVC5UEfwR1N-c76qv61o?usp=sharing)
2. [Table-Top Manipulation (Robot Arm's View and Top View)](https://drive.google.com/drive/folders/1Q8oNpAawJZmGR3u9g2gmIVVpLsN7W1aM?usp=sharing)
3. [Table-Top Manipulation (Side View)](https://drive.google.com/drive/folders/17HsMV-YMzkFRAB9NQ6LoDPnEwaIiTgYV?usp=sharing)

### Training
[Carla Images](https://drive.google.com/drive/folders/1j34A-vWG0oMdAjfCZDZIaKHr4AeZ5iPU?usp=sharing)

### Testing
[Real-World Driving](https://drive.google.com/drive/folders/1Pg5c4Gp6KF7n0Oy22gaz9gXYh8TPuIBJ?usp=sharing)

### Sample Images for Inference
[Inference Samples](https://huggingface.co/datasets/anonymous-yyh-1971/hf_dataset/tree/main)

## Citation

If you find this work interesting and use it in your research, please consider citing our paper.
```
@misc{bhatt2024knowyoureuncertainplanning,
      title={Know Where You're Uncertain When Planning with Multimodal Foundation Models: A Formal Framework}, 
      author={Neel P. Bhatt and Yunhao Yang and Rohan Siva and Daniel Milan and Ufuk Topcu and Zhangyang Wang},
      year={2024},
      eprint={2411.01639},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2411.01639}, 
}
```

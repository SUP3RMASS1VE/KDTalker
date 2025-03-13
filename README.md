<div align="center">

# Unlock Pose Diversity: Accurate and Efficient Implicit Keypoint-based Spatiotemporal Diffusion for Audio-driven Talking Portrait
[![arXiv](https://img.shields.io/badge/arXiv-KDTalker-9065CA.svg?logo=arXiv)](http://arxiv.org/abs/)
[![License](https://img.shields.io/badge/license-CC--BY--NC%204.0-green)](https://creativecommons.org/licenses/by-nc/4.0/)
[![GitHub Stars](https://img.shields.io/github/stars/chaolongy/KDTalker?style=social)](https://github.com/chaolongy/KDTalker)

</div>
<div align="justify">

# Comparative videos
https://github.com/user-attachments/assets/08ebc6e0-41c5-4bf4-8ee8-2f7d317d92cd


# Demo


# Environment
Our KDTalker could be conducted on one RTX4090 or RTX3090.

### 1. Clone the code and prepare the environment
```
git clone https://github.com/chaolongy/KDTalker
cd KDTalker

conda create -n KDTalker python=3.9
conda activate KDTalker
pip install torch==2.3.0 torchvision==0.18.0 torchaudio==2.3.0 --index-url https://download.pytorch.org/whl/cu118
conda install pytorch==2.3.0 torchvision==0.18.0 torchaudio==2.3.0 pytorch-cuda=11.8 -c pytorch -c nvidia
pip install -r requirements.txt
```

### 2. Download pretrained weights
First, you can download all LiverPorait pretrained weights from [Google Drive](https://drive.google.com/drive/folders/1UtKgzKjFAOmZkhNK-OYT0caJ_w2XAnib) or [Baidu Yun](https://pan.baidu.com/s/1MGctWmNla_vZxDbEp2Dtzw?pwd=z5cn). Unzip and place them in `./dataset_process/pretrained_weights`.
Ensuring the directory structure is as follows:
```text
pretrained_weights
├── insightface
│   └── models
│       └── buffalo_l
│           ├── 2d106det.onnx
│           └── det_10g.onnx
└── liveportrait
    ├── base_models
    │   ├── appearance_feature_extractor.pth
    │   ├── motion_extractor.pth
    │   ├── spade_generator.pth
    │   └── warping_module.pth
    ├── landmark.onnx
    └── retargeting_models
        └── stitching_retargeting_module.pth
```
Second, you can download KDTalker weights from [Google Drive](https://drive.google.com/drive/). Put it in `./dtaset_process/ckpts`.



# Inference
```
python inference.py
```


# Contact
Our code is under the CC-BY-NC 4.0 license and intended solely for research purposes. If you have any questions or wish to use it for commercial purposes, please contact us at chaolong.yang@liverpool.ac.uk


# Citation
If you find this code helpful for your research, please cite:
```

```


# Acknowledge
We acknowledge these works for their public code and selfless help: [SadTalker](https://github.com/OpenTalker/SadTalker), [LivePortrait](https://github.com/KwaiVGI/LivePortrait), [Wav2Lip](https://github.com/Rudrabha/Wav2Lip), [Face-vid2vid](https://github.com/zhanglonghao1992/One-Shot_Free-View_Neural_Talking_Head_Synthesis) etc.
</div>

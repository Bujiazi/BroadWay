<div align="center">

<h1>BroadWay: Boost Your Text-to-Video Generation Model in <br>a Training-free Way</h1>

<div>
    <a href="https://github.com/Bujiazi/" target="_blank">Jiazi Bu*</a><sup></sup> | 
    <a href="https://github.com/LPengYang/" target="_blank">Pengyang Ling*</a><sup></sup> | 
    <a href="https://panzhang0212.github.io/" target="_blank">Pan Zhang<sup>†</sup></a><sup></sup> | 
    <a href="https://wutong16.github.io/" target="_blank">Tong Wu</a><sup></sup> |
    <a href="https://scholar.google.com/citations?user=FscToE0AAAAJ&hl=en/" target="_blank">Xiaoyi Dong</a><sup></sup> |
    <a href="https://yuhangzang.github.io/" target="_blank">Yuhang Zang</a><sup></sup> |
    <a href="https://scholar.google.com/citations?hl=zh-CN&user=sJkqsqkAAAAJ" target="_blank">Yuhang Cao</a><sup></sup> |
    <a href="http://dahua.site/" target="_blank">Dahua Lin</a><sup></sup> |
    <a href="https://myownskyw7.github.io/" target="_blank">Jiaqi Wang<sup>†</sup></a><sup></sup>
</div>
<br>
<div>
    <sup></sup>Shanghai Jiao Tong University, University of Science and Technology of China, <br> The Chinese University of Hong Kong, Shanghai Artificial Intelligence Laboratory
</div>
(*<b>Equal Contribution</b>)(<sup>†</sup><b>Corresponding Author</b>)
<br><br>

[![arXiv](https://img.shields.io/badge/arXiv-2410.06241-b31b1b.svg)](https://arxiv.org/abs/2410.06241) [![Project Page](https://img.shields.io/badge/Project-Website-green)](https://bujiazi.github.io/motionclone.github.io/) ![](https://img.shields.io/github/stars/Bujiazi/BroadWay?style=social) 

---

<strong>BroadWay provides a training-free and plug-and-play option to enhance the overall quality of current T2V backbones.</strong>

<div style="width: 100%; text-align: center; margin:auto;">
    <img style="width:100%" src="__assets__/pipeline.png">
</div>
<br>

<details><summary>📖 Click for the full abstract of BroadWay</summary>

> The text-to-video (T2V) generation models, offering convenient visual creation, have recently garnered increasing attention. Despite their substantial potential, the generated videos may present artifacts, including structural implausibility, temporal inconsistency, and a lack of motion, often resulting in near-static video. In this work, we have identified a correlation between the disparity of temporal attention maps across different blocks and the occurrence of temporal inconsistencies. Additionally, we have observed that the energy contained within the temporal attention maps is directly related to the magnitude of motion amplitude in the generated videos. Based on these observations, we present **BroadWay**, a training-free method to improve the quality of text-to-video generation without introducing additional parameters, augmenting memory or sampling time. Specifically, BroadWay is composed of two principal components: 1) Temporal Self-Guidance improves the structural plausibility and temporal consistency of generated videos by reducing the disparity between the temporal attention maps across various decoder blocks. 2) Fourier-based Motion Enhancement enhances the magnitude and richness of motion by amplifying the energy of the map. Extensive experiments demonstrate that BroadWay significantly improves the quality of text-to-video generation with negligible additional cost.
</details>

</div>

## 🎈Demo

<div align="center">

[![]](https://github.com/user-attachments/assets/37a2c14d-d9ee-484c-b1c7-344b6af96485)

[![]](https://github.com/user-attachments/assets/e3289514-0ba8-4a6f-b792-58e4f78fc5db)

</div>

## 💻 BroadWay Code


## 📎 Citation 

If you find this work helpful, please cite the following paper:

```
@article{bu2024broadway,
  title={BroadWay: Boost Your Text-to-Video Generation Model in a Training-free Way},
  author={Bu, Jiazi and Ling, Pengyang and Zhang, Pan and Wu, Tong and Dong, Xiaoyi and Zang, Yuhang and Cao, Yuhang and Lin, Dahua and Wang, Jiaqi},
  journal={arXiv preprint arXiv:2410.06241},
  year={2024}
}
```

## 📣 Disclaimer

This is official code of [BroadWay](https://arxiv.org/abs/2410.06241).
All the copyrights of the demo images and audio are from community users. 
Feel free to contact us if you would like remove them.

## 💞 Acknowledgements
The code is built upon the below repositories, we thank all the contributors for open-sourcing.
* [AnimateDiff](https://github.com/guoyww/AnimateDiff)
* [VideoCrafter](https://github.com/AILab-CVC/VideoCrafter)

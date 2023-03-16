# T2I Adapter Diffusers + ONNX + TensorRT

Convert and Inference T2I-Adapter models in ONNX and TensorRT. Polygraphy is used to convert from onnx to tensorrt and create engine file.

see [t2i_adapter_trt.ipynb](https://github.com/ffletcherr/t2i-adapter-diffusers/blob/master/t2i_adapter_trt.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ffletcherr/t2i-adapter-diffusers/blob/master/t2i_adapter_trt.ipynb)

_______________


Original Image             |  Converted by Canny Adapter
:-------------------------:|:-------------------------:
![](contents/table.png)  |  ![](contents/new-table.png)



## References

[convert_stable_diffusion_checkpoint_to_onnx.py](https://github.com/huggingface/diffusers/blob/eadf0e2555cfa19b033e02de53553f71ac33536f/scripts/convert_stable_diffusion_checkpoint_to_onnx.py)

[t2i-adapter-diffusers](https://github.com/cloneofsimo/t2i-adapter-diffusers)

[T2I-Adapter](https://github.com/TencentARC/T2I-Adapter)

```bibtex
@misc{https://doi.org/10.48550/arxiv.2302.08453,
  doi = {10.48550/ARXIV.2302.08453},
  url = {https://arxiv.org/abs/2302.08453},
  author = {Mou, Chong and Wang, Xintao and Xie, Liangbin and Zhang, Jian and Qi, Zhongang and Shan, Ying and Qie, Xiaohu},
  keywords = {Computer Vision and Pattern Recognition (cs.CV), Artificial Intelligence (cs.AI), Machine Learning (cs.LG), Multimedia (cs.MM), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {T2I-Adapter: Learning Adapters to Dig out More Controllable Ability for Text-to-Image Diffusion Models},
  publisher = {arXiv},
  year = {2023},
  copyright = {Creative Commons Attribution 4.0 International}
}
```

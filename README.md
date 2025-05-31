# LCM-Dataset
The open-source datasets of Large Circuit Model


DeepCircuitX provides a holistic, multilevel resource that spans repository, file, module, and block-level RTL code and corresponding annotations. Our dataset enables more nuanced training and evaluation of large language models (LLMs) for RTL-specific tasks. 

The detail you can find in the link: 
```
https://zeju.gitbook.io/lcm-team/deepcircuitx/introduction-of-our-dataset
```

ForgeEDA is an open-source, multifaceted dataset comprising 1,189 practical circuit designs across 6 categories: Processor, Arithmetic, Encoder/Decoder, Interface, Controller. ForgeEDA includes diverse circuit representations such as Register Transfer Level (RTL) code, Post- mapping (PM) netlists, And-Inverter Graphs (AIGs), and placed netlists, enabling comprehensive analysis and development.

The module-level AIGs can be found in this link:
```
https://huggingface.co/datasets/zshi0616/ForgeEDA_AIG/tree/main
```

PM netlists and reports are coming soon. 

# Citation

If you find our work useful, please consider citing:
```
@article{li2025deepcircuitx,
  title={Deepcircuitx: A comprehensive repository-level dataset for rtl code understanding, generation, and ppa analysis},
  author={Li, Zeju and Xu, Changran and Shi, Zhengyuan and Peng, Zedong and Liu, Yi and Zhou, Yunhao and Zhou, Lingfeng and Ma, Chengyu and Zhong, Jianyuan and Wang, Xi and others},
  journal={arXiv preprint arXiv:2502.18297},
  year={2025}
}

@article{shi2025forgeeda,
  title={ForgeEDA: A Comprehensive Multimodal Dataset for Advancing EDA},
  author={Shi, Zhengyuan and Li, Zeju and Ma, Chengyu and Zhou, Yunhao and Zheng, Ziyang and Liu, Jiawei and Pan, Hongyang and Zhou, Lingfeng and Li, Kezhi and Zhu, Jiaying and others},
  journal={arXiv preprint arXiv:2505.02016},
  year={2025}
}
```



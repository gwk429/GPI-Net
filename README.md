# GPI-Net: Gestalt-Guided Parallel Interaction Network via Orthogonal Geometric Consistency for Robust Point Cloud Registration (IJCAI-2025)
PyTorch implementation of the paper 'GPI-Net'

Weikang Gu, Mingyue Han, Li Xue, Heng Dong, Changcai Yang, Riqing Chen, Lifang Wei

1. 训练室内场景3DMatch数据集以及3DLoMatch数据集
run：python train_3DMatch.py
2. 训练室外场景KITTI数据集
run：python train_KITTI.py
3. 测试3DMatch,3DLoMatch,KITTI分别
run: python test_3DMatch.py, test_3DLoMatch.py, test_KITTI.py

# Citation
<details>
  <summary>Click to view the citation</summary>

  ```bibtex
  @inproceedings{ijcai2025p118,
      title     = {{GPI}-{Net}: {Gestalt}-{Guided} {Parallel} {Interaction} {Network} {via} {Orthogonal} {Geometric} {Consistency} for {Robust} {Point} {Cloud} {Registration}},
      author    = {Gu, Weikang and Han, Mingyue and Xue, Li and Dong, Heng and Yang, Changcai and Chen, Riqing and Wei, Lifang},
      booktitle = {Proceedings of the Thirty-Fourth International Joint Conference on
      Artificial Intelligence, {IJCAI-25}},
      pages     = {1053--1061},
      year      = {2025},
      doi       = {10.24963/ijcai.2025/118},
  }

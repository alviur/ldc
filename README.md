# Exemplar-free Continual Representation Learning via Learnable Drift Compensation

This is the official repository for the paper:
> **[Exemplar-free Continual Representation Learning via Learnable Drift Compensation](https://arxiv.org/abs/)**<br>
> [Alex Gomez-Villa](https://scholar.google.com/citations?user=A2dhwNgAAAAJ&hl=en), [Dipam Goswami](https://scholar.google.com/citations?user=6_aj45AAAAAJ&hl), [Kai Wang](https://scholar.google.com/citations?user=j14vd0wAAAAJ&hl),  [Andrew D. Bagdanov](https://scholar.google.com/citations?user=_Fk4YUcAAAAJ&hl),[Bartlomiej Twardowski](https://scholar.google.com/citations?user=8yywECgAAAAJ&hl),  [Joost van de Weijer](https://scholar.google.com/citations?user=Gsw2iUEAAAAJ&hl)<br>
> **ECCV 2024**

> **Abstract:** *Exemplar-free class-incremental learning using a backbone trained from scratch and starting from a small first task presents a significant challenge for continual representation learning. Prototype-based approaches, when continually updated, face the critical issue of semantic drift due to which the old class prototypes drift to different positions in the new feature space.
Through an analysis of forgetting in prototype-based continual learning, we show that forgetting is not due to diminished discriminative power of the feature extractor, and can potentially be corrected by drift compensation. 
To address this, we propose a novel feature drift correction method called Learnable Drift Compensation (LDC). LDC can effectively mitigate drift in any moving backbone, whether supervised or unsupervised. LDC is fast and straightforward to integrate on top of existing continual learning approaches. Finally, we showcase how LDC can be applied in combination with self-supervised CL methods, resulting in the first exemplar-free semi-supervised continual learning approach. We achieve state-of-the-art performance in both supervised and semi-supervised settings across multiple datasets.*
<be>
# Citation
If you like our work, please cite our [paper](https://arxiv.org/):
```
@inproceedings{gomezvilla2024,
  title={Exemplar-free Continual Representation Learning via Learnable Drift Compensation},
  author={Gomez-Villa, Alex and Goswami, Dipam and Wang, Kai and Bagdanov Andrew and Twardowski, Bartlomiej  and van de Weijer, Joost},
  booktitle={IEEE/CVF European Conference on Computer Vision},
  year={2024}
}

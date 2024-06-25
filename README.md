# Awesome-AI-Generated-Video-Detection
✨✨Latest Papers on AI-Generated Video Detection and Related Areas

## Contents
- [Survey](#survey)
- [Dataset](#dataset)
- [Competition](#competition)
- [Paper](#papers)


## Survey
| Title                                                        | Venue       | Year |
| :----------------------------------------------------------- | ----------- | ---- |
|[A Survey on Deepfake Video Detection](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/bme2.12031) | IET Biometrics | 2021 

## Dataset
| Dataset|Title                                                        | Venue       | Year |       Task     |
| :--------------------------- | -------------------------------- | ----------- | ---- | -------------- |
| GenVideo| [DeMamba: AI-Generated Video Detection on Million-Scale GenVideo Benchmark](https://arxiv.org/abs/2405.19707)| arXiv | 2024 | General
| GenVidDet| [Distinguish Any Fake Videos: Unleashing the Power of Large-scale Data and Motion Features](https://arxiv.org/pdf/2405.15343)| arXiv | 2024 | General
| Faceforensics| [Faceforensics: A large-scale video dataset for forgery detection in human faces](https://arxiv.org/abs/1803.09179)| arXiv | 2018 | Face
| FakeAVCeleb | [FakeAVCeleb: A Novel Audio-Video Multimodal Deepfake Dataset](https://arxiv.org/abs/2108.05080)| NeurIPS Datasets and Benchmarks Track| 2021 | Face

## Competition
| Name|Link  | Year | 
| :--------------------------- | ------------- | ----------- | 
|DFAD@CVPR| https://www.dfad.unimore.it/challenge/| 2024


## Papers

| Title                                                        | Venue       | Year |       Task     |   Insights                       | Code if available                                                     |
| :----------------------------------------------------------- | ----------- | ---- | ---- |------------------------------------------------------------ | ---------------------------------------------------- |
| [Turns Out I’m Not Real: Towards Robust Detection of AI-Generated Videos](https://arxiv.org/pdf/2406.09601) | arXiv        | 2024 |   General Detection  | Dire frame & CNN + LSTM detector| N/A
| [DeMamba: AI-Generated Video Detection on Million-Scale GenVideo Benchmark](https://arxiv.org/abs/2405.19707) | arXiv        | 2024 |   General Detection  |Detail Mamba modeling spatial-temporal artifacts| [Code](https://github.com/chenhaoxing/DeMamba)
| [Distinguish Any Fake Videos: Unleashing the Power of Large-scale Data and Motion Features](https://arxiv.org/pdf/2405.15343) | arXiv   | 2024 |   General Detection  |Dual path feature fusing: sptial-temporal and optical flow| N/A
| [DeCoF: Generated Video Detection via Frame Consistency](https://arxiv.org/pdf/2402.02085) | arXiv        | 2024 |   General Detection  |Video-based, CLIP+Transformer modeling temporal artifacts| N/A 
| [TALL: Thumbnail Layout for Deepfake Video Detection](https://openaccess.thecvf.com/content/ICCV2023/papers/Xu_TALL_Thumbnail_Layout_for_Deepfake_Video_Detection_ICCV_2023_paper.pdf) | ICCV        | 2023 |   Face Detection  | Transforms a video clip into a pre-defined layout to realize the preservation of spatial and temporal dependencies| [Code](https://github.com/rainy-xu/TALL4Deepfake)
| [ISTVT: Interpretable Spatial-Temporal Video Transformer for Deepfake Detection](https://ieeexplore.ieee.org/abstract/document/10024806)| TIFS        | 2023 |   Face Detection  |Decomposed spatial-temporal self-attention and a self-subtract mechanism to capture spatial artifacts and temporal inconsistency| N/A 
| [Exploiting Complementary Dynamic Incoherence for DeepFake Video Detection](https://ieeexplore.ieee.org/abstract/document/10023530) | TCSVT | 2023 | Face Detection| Dynamic facial feature analysis |N/A
| [Hierarchical Contrastive Inconsistency Learning for Deepfake Video Detection](https://link.springer.com/chapter/10.1007/978-3-031-19775-8_35) | ECCV        | 2022 |   Face Detection  | Hierarchical contrastive inconsistency learning | N/A 
| [Spatiotemporal Inconsistency Learning for DeepFake Video Detection](https://arxiv.org/pdf/2109.01860) | ACM MM        | 2021 |   Face Detection  |Video-based, STIL modeling spatiotemporal artifacts| [Code](https://github.com/Tencent/TFace)

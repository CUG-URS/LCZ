# MAGNET: Multi-scAle Geography-aware deliNeation for Enhanced LCZ Transferability
MAGNET is a novel, dynamic multi-modal framework for fine-grained Local Climate Zone (LCZ) mapping.

# MAGNET-LCZ-Mapping-Results
Version 1.0

## 1.Overview
This study makes four key contributions: 1) Dynamic geo-semantic feedback for adaptive cross-modal fusion: Geographic priors—such as impervious/pervious surface ratios and 3D morphology metrics are mathematically embedded into end-to-end model training through geo-aware
gradient backpropagation. This mechanism facilitates adaptive weighting between the two branches based on local scene composition such as prioritizing morphological features in dense built-up cores or spectral features in rural-urban transition zones, markedly enhancing
the model’s cross-regional transferability and interpretability of fusion processes. 2) Cross-modal 2D-3D integration: A dual-branch coupling mechanism with cross-scale interaction unifies Sentinel-2 imagery and building morphology, overcoming the static fusion bottleneck
of existing LCZ methods. This ensures fine-grained semantic coupling between spectral, textural, and morphological information. 3) Scalable geo-entity mapping paradigm: We design a context-aware mapping paradigm that adaptively selects pixel-, scene-, or parcel-based units
according to spatial structure. This reduces boundary fragmentation for linear/polygonal features (e.g., rivers, residential blocks) and improves delineation accuracy in fragmented, irregular, or heterogeneous landscapes. 4) Large-scale validation and product: Independent
validation is conducted using hold-out samples from five geographically and socio-economically distinct global cities (USA, Africa, South America, Europe, Asia) with transparent sampling and response design. MAGNET achieves up to 15.85% higher delineation accuracy in
fragmented morphologies and 5–10% improvement over state-of-the-art methods—exceeding the gains of recent baselines. We publicly release fine-grained LCZ maps for 40 global cities (including 34 Chinese provincial capitals) along with code and trained models at 
https://github.com/CUG-URS/LCZ, providing a scalable, transferable, and openly accessible benchmark for climate-sensitive urban mapping in support of SDG 11 (Sustainable Cities and Communities) and SDG 13 (Climate Action).
                                                              <img width="694" height="421" alt="image" src="https://github.com/CUG-URS/LCZ/blob/main/figure/Study%20areas.png" />
                                                              <img width="689" height="615" alt="image" src="https://github.com/CUG-URS/LCZ/blob/main/figure/MAGNET%20framework.png" />
                                                              <img width="701" height="991" alt="image" src="https://github.com/CUG-URS/LCZ/blob/main/figure/Mapping%20results.png" />

### 2.Download

 - [BaiduYun]( https://pan.baidu.com/s/15-fxgGHDBsU6H6o0Nr3pqA?pwd=gti3 ) Download link: （Password: gti3）

## 6.Contact
If you have any problem in using the CHN10-CUG Roads Dataset, please contact: yunchangzhang@cug.edu.cn

For any possible research collaboration, please contact Prof. Qiqi Zhu (zhuqq@cug.edu.cn).

The homepage of our academic group is: http://grzy.cug.edu.cn/zhuqiqi/en/index.htm.

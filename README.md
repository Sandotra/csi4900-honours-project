# CSI 4900 Honours Project (Fall 2026)

**Working title:** Foundation-Model Similarity Measures for Test-Input Validation in Vision Deep Learning Systems

**Team:** Suryadev Andotra and Albert Hou
**Supervisor:** Prof. Shiva Nejati (snejati@uottawa.ca), confirmed Sep 15, 2026
**Coordinator:** Prof. Paola Flocchini. Course page: https://www.site.uottawa.ca/~flocchin/CSI4900/

## The project in one paragraph
We build on HiL-TV (Ghobari et al., ICSE-SEIP 2025, arXiv 2501.01606), which decides whether a transformed test image (darker, foggier, compressed) is still valid by feeding 13 image-similarity measures to a random forest inside a human-in-the-loop labelling loop. **Addition A:** add similarity measures from foundation models (CLIP, DINOv2, a CLIP zero-shot car/not-car check) and measure the accuracy gain for the same human effort. **Addition B:** replace the loop's random choice of images for the human with uncertainty-based selection and measure the effort saved. Both are evaluated on the public CIFAR-10 pairs from the paper's replication package.

## Setup
```
git clone https://github.com/delaramGh/ICSE2025Industry external/ICSE2025Industry
```
The replication package has no licence file, so it stays out of this repository until Nejati confirms we may reuse it.

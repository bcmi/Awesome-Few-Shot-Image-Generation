# Awesome Few-Shot Image Generation  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources including papers, datasets, and relevant links pertaining to few-shot image generation.


## From Base Categories to Novel Categories

**Optimization-based methods:**
+ Louis Clouâtre, Marc Demers: "*FIGR: Few-shot Image Generation with Reptile.*" CoRR abs/1901.02199 (2019) [[pdf]](https://arxiv.org/pdf/1901.02199.pdf) [[code]](https://arxiv.org/pdf/1901.02199.pdf)
+ Weixin Liang, Zixuan Liu, Can Liu: "*DAWSON: A Domain Adaptive Few Shot Generation Framework.*" CoRR abs/2001.00576 (2020) [[pdf]](https://arxiv.org/pdf/2001.00576.pdf) [[code]](https://github.com/LC1905/musegan/)

**Fusion-based methods:**
+ Davis Wertheimer, Omid Poursaeed, Bharath Hariharan: "*Augmentation-interpolative Autoencoders for Unsupervised Few-shot Image Generation.*" arXiv (2020). [[pdf]](https://arxiv.org/pdf/2011.13026.pdf)
+ Yan Hong, Li Niu, Jianfu Zhang, Weijie Zhao, Chen Fu, Liqing Zhang: "*F2GAN: Fusing-and-Filling GAN for Few-shot Image Generation.*" ACM MM (2020) [[pdf]](https://arxiv.org/pdf/2008.01999.pdf) [[code]](https://github.com/bcmi/F2GAN-Few-Shot-Image-Generation)
+ Yan Hong, Li Niu, Jianfu Zhang, Liqing Zhang: "*MatchingGAN: Matching-based Few-shot Image Generation.*" ICME (2020) [[pdf]](https://arxiv.org/pdf/2003.03497.pdf) [[code]](https://github.com/bcmi/MatchingGAN-Few-Shot-Image-Generation)
+ Sergey Bartunov, Dmitry P. Vetrov: "*Few-shot Generative Modelling with Generative Matching Networks.*" AISTATS (2018) [[pdf]](http://proceedings.mlr.press/v84/bartunov18a/bartunov18a.pdf) [[code]](https://github.com/sbos/gmn)

**Transformation-based methods:**
+ Antreas Antoniou, Amos J. Storkey, Harrison Edwards: "*Data Augmentation Generative Adversarial Networks.*" stat (2018) [[pdf]](https://arxiv.org/pdf/1711.04340.pdf) [[code]](https://github.com/AntreasAntoniou/DAGAN) 
+ Yan Hong, Li Niu, Jianfu Zhang, Jing Liang, Liqing Zhang: "*DeltaGAN: Towards Diverse Few-shot Image Generation with Sample-Specific Delta.*" CoRR abs/2009.08753 (2020) [[pdf]](https://arxiv.org/pdf/2009.08753.pdf)

**Datasets:**
+ Omniglot:  1623 handwritten characters from 50 different alphabets. Each of the 1623 characters was drawn online via Amazon's Mechanical Turk by 20 different people [[link]](https://github.com/brendenlake/omniglot/)
+ EMNIST:  47 balanced classes [[link]](https://www.nist.gov/itl/products-and-services/emnist-dataset)
+ FIGR: 17,375 classes of 1,548,256 images representing pictograms, ideograms, icons, emoticons or object or conception depictions [[link]](https://github.com/marcdemers/FIGR-8)
+ VGG-Faces:  2395 categories [[link]](https://drive.google.com/drive/folders/15x2C11OrNeKLMzBDHrv8NPOwyre6H3O5)
+ Flowers:  8189 images from 102 flower classes [[link]](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/)
+ Animal Faces: 117574 images from 149 animal classes [[link]](https://github.com/NVlabs/FUNIT)

## From Large Dataset to Small Dataset

+ Atsuhiro Noguchi, Tatsuya Harada: "*Image generation from small datasets via batch statistics adaptation.*" ICCV (2019). [[pdf]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Noguchi_Image_Generation_From_Small_Datasets_via_Batch_Statistics_Adaptation_ICCV_2019_paper.pdf) [[code]](http://github.com/nogu-atsu/small-dataset-image-generation)
+ Yaxing Wang, Abel Gonzalez-Garcia, David Berga, Luis Herranz, Fahad Shahbaz Khan, Joost van de Weijer: "*MineGAN: effective knowledge transfer from GANs to target domains with few images.*" CVPR (2020). [[pdf]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_MineGAN_Effective_Knowledge_Transfer_From_GANs_to_Target_Domains_With_CVPR_2020_paper.pdf) [[code]](https://github.com/yaxingwang/MineGAN)
+  Yijun Li, Richard Zhang, Jingwan Lu, Eli Shechtman: "*Few-shot Image Generation with Elastic Weight Consolidation.*" NeurIPS (2020). [[pdf]](ttps://arxiv.org/pdf/2012.02780.pdf) 
+ Esther Robb, Wen-Sheng Chu, Abhishek Kumar, Jia-Bin Huang: "*Few-Shot Adaptation of Generative Adversarial Networks.*" arXiv (2020). [[pdf]](https://arxiv.org/pdf/2010.11943.pdf) [[code]](https://github.com/e-271/few-shot-gan)
+ Miaoyun Zhao, Yulai Cong, Lawrence Carin: "*On Leveraging Pretrained GANs for Generation with Limited Data.*" ICML (2020). [[pdf]](http://proceedings.mlr.press/v119/zhao20a/zhao20a.pdf) [[code]](https://github.com/MiaoyunZhao/GANTransferLimitedData)
+ Utkarsh Ojha, Yijun Li, Jingwan Lu, Alexei A. Efros, Yong Jae Lee, Eli Shechtman, Richard Zhang: "*Few-shot Image Generation via Cross-domain Correspondence.*" CVPR (2021). [[pdf]](https://arxiv.org/pdf/2104.06820.pdf) [[code]](https://github.com/utkarshojha/few-shot-gan-adaptation)

## Only Small Dataset

+ Shengyu Zhao, Zhijian Liu, Ji Lin, Jun-Yan Zhu, Song Han: "*Differentiable Augmentation for Data-Efficient GAN Training.*" NeurIPS (2020). [[pdf]](https://arxiv.org/pdf/2006.10738.pdf) [[code]](https://github.com/mit-han-lab/data-efficient-gans)
+ Bingchen Liu, Yizhe Zhu, Kunpeng Song, Ahmed Elgammal: "*Towards Faster and Stabilized GAN Training for High-fidelity Few-shot Image Synthesis.*" ICLR (2021).               [[pdf]](https://arxiv.org/pdf/2101.04775v1.pdf) [[code]](https://github.com/odegeasslbc/FastGAN-pytorch)


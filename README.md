# Awesome Few-Shot Image Generation  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources including papers, datasets, and relevant links pertaining to few-shot image generation. Since few-shot image generation is a very broad concept, there are various experimental settings and research lines in the realm of few-shot image generation. 


## From Base Categories to Novel Categories
The generative model is trained on base categories and applied to novel categories with (optimization-based) or without finetuning (fusion-based and transformation-based). 

**Optimization-based methods:**
+ Louis Clouâtre, Marc Demers: "*FIGR: Few-shot Image Generation with Reptile.*" CoRR abs/1901.02199 (2019) [[pdf]](https://arxiv.org/pdf/1901.02199.pdf) [[code]](https://arxiv.org/pdf/1901.02199.pdf)
+ Weixin Liang, Zixuan Liu, Can Liu: "*DAWSON: A Domain Adaptive Few Shot Generation Framework.*" CoRR abs/2001.00576 (2020) [[pdf]](https://arxiv.org/pdf/2001.00576.pdf) [[code]](https://github.com/LC1905/musegan/)

**Fusion-based methods:**
+ Sergey Bartunov, Dmitry P. Vetrov: "*Few-shot Generative Modelling with Generative Matching Networks.*" AISTATS (2018) [[pdf]](http://proceedings.mlr.press/v84/bartunov18a/bartunov18a.pdf) [[code]](https://github.com/sbos/gmn)
+ Davis Wertheimer, Omid Poursaeed, Bharath Hariharan: "*Augmentation-interpolative Autoencoders for Unsupervised Few-shot Image Generation.*" arXiv (2020). [[pdf]](https://arxiv.org/pdf/2011.13026.pdf)
+ Yan Hong, Li Niu, Jianfu Zhang, Liqing Zhang: "*MatchingGAN: Matching-based Few-shot Image Generation.*" ICME (2020) [[pdf]](https://arxiv.org/pdf/2003.03497.pdf) [[code]](https://github.com/bcmi/MatchingGAN-Few-Shot-Image-Generation)
+ Yan Hong, Li Niu, Jianfu Zhang, Weijie Zhao, Chen Fu, Liqing Zhang: "*F2GAN: Fusing-and-Filling GAN for Few-shot Image Generation.*" ACM MM (2020) [[pdf]](https://arxiv.org/pdf/2008.01999.pdf) [[code]](https://github.com/bcmi/F2GAN-Few-Shot-Image-Generation)
+ Zheng Gu, Wenbin Li, Jing Huo, Lei Wang, Yang Gao: "*Lofgan: Fusing local representations for fewshot image generation.*" ICCV (2021) [[pdf]](https://openaccess.thecvf.com/content/ICCV2021/papers/Gu_LoFGAN_Fusing_Local_Representations_for_Few-Shot_Image_Generation_ICCV_2021_paper.pdf) [[code]](https://github.com/edward3862/LoFGAN-pytorch)

**Transformation-based methods:**
+ Antreas Antoniou, Amos J. Storkey, Harrison Edwards: "*Data Augmentation Generative Adversarial Networks.*" stat (2018) [[pdf]](https://arxiv.org/pdf/1711.04340.pdf) [[code]](https://github.com/AntreasAntoniou/DAGAN) 
+  Guanqi Ding, Xinzhe Han, Shuhui Wang, Shuzhe Wu, Xin Jin, Dandan Tu, Qingming Huang: "*Attribute Group Editing for Reliable Few-shot Image Generation.*" CVPR (2022) [[pdf]](https://arxiv.org/pdf/2203.08422.pdf) [[code]](https://github.com/UniBester/AGE)
+ Yan Hong, Li Niu, Jianfu Zhang, Liqing Zhang: "*Few-shot Image Generation Using Discrete Content Representation.*" ACM MM (2022) [[pdf]](https://arxiv.org/pdf/2207.10833.pdf)
+ Yan Hong, Li Niu, Jianfu Zhang, Liqing Zhang: "*DeltaGAN: Towards Diverse Few-shot Image Generation with Sample-Specific Delta.*" ECCV (2022) [[pdf]](https://arxiv.org/pdf/2009.08753.pdf) [[code]](https://github.com/bcmi/DeltaGAN-Few-Shot-Image-Generation)

**Datasets:**
+ Omniglot:  1623 handwritten characters from 50 different alphabets. Each of the 1623 characters was drawn online via Amazon's Mechanical Turk by 20 different people [[link]](https://github.com/brendenlake/omniglot/)
+ EMNIST:  47 balanced classes [[link]](https://www.nist.gov/itl/products-and-services/emnist-dataset)
+ FIGR: 17,375 classes of 1,548,256 images representing pictograms, ideograms, icons, emoticons or object or conception depictions [[link]](https://github.com/marcdemers/FIGR-8)
+ VGG-Faces:  2395 categories [[link]](https://drive.google.com/drive/folders/15x2C11OrNeKLMzBDHrv8NPOwyre6H3O5)
+ Flowers:  8189 images from 102 flower classes [[link]](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/)
+ Animal Faces: 117574 images from 149 animal classes [[link]](https://github.com/NVlabs/FUNIT)

## From Large Dataset to Small Dataset

The generative model is trained on a large dataset (base domain/category) and transferred to a small dataset (novel domain/category). 

**Finetuning-based methods:** Only finetune a part of the model parameters *or* train a few additional parameters.
+ Atsuhiro Noguchi, Tatsuya Harada: "*Image generation from small datasets via batch statistics adaptation.*" ICCV (2019) [[pdf]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Noguchi_Image_Generation_From_Small_Datasets_via_Batch_Statistics_Adaptation_ICCV_2019_paper.pdf) [[code]](http://github.com/nogu-atsu/small-dataset-image-generation)
+ Esther Robb, Wen-Sheng Chu, Abhishek Kumar, Jia-Bin Huang: "*Few-Shot Adaptation of Generative Adversarial Networks.*" arXiv (2020) [[pdf]](https://arxiv.org/pdf/2010.11943.pdf) [[code]](https://github.com/e-271/few-shot-gan)
+ Miaoyun Zhao, Yulai Cong, Lawrence Carin: "*On Leveraging Pretrained GANs for Generation with Limited Data.*" ICML (2020) [[pdf]](http://proceedings.mlr.press/v119/zhao20a/zhao20a.pdf) [[code]](https://github.com/MiaoyunZhao/GANTransferLimitedData)
+ Yaxing Wang, Abel Gonzalez-Garcia, David Berga, Luis Herranz, Fahad Shahbaz Khan, Joost van de Weijer: "*MineGAN: effective knowledge transfer from GANs to target domains with few images.*" CVPR (2020) [[pdf]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_MineGAN_Effective_Knowledge_Transfer_From_GANs_to_Target_Domains_With_CVPR_2020_paper.pdf) [[code]](https://github.com/yaxingwang/MineGAN)
+ Yunqing Zhao, Keshigeyan Chandrasegaran, Milad Abdollahzadeh, Ngai-Man Cheung: "*Few-shot Image Generation via Adaptation-Aware Kernel Modulation.*" NeurIPS (2022) [[pdf]](https://arxiv.org/pdf/2210.16559.pdf) [[code]](https://github.com/yunqing-me/AdAM)
+ Yuxuan Duan, Li Niu, Yan Hong, Liqing Zhang: "*WeditGAN: Few-shot Image Generation via Latent Space Relocation.*" arXiv (2023) [[pdf]](https://arxiv.org/pdf/2305.06671.pdf)

**Regularization-based methods:** Regularize the transfer process based on the prior regularization knowledge, usually by imposing penalty on parameter/feature changes.
+  Yijun Li, Richard Zhang, Jingwan Lu, Eli Shechtman: "*Few-shot Image Generation with Elastic Weight Consolidation.*" NeurIPS (2020) [[pdf]](https://arxiv.org/pdf/2012.02780.pdf) 
+ Utkarsh Ojha, Yijun Li, Jingwan Lu, Alexei A. Efros, Yong Jae Lee, Eli Shechtman, Richard Zhang: "*Few-shot Image Generation via Cross-domain Correspondence.*" CVPR (2021) [[pdf]](https://arxiv.org/pdf/2104.06820.pdf) [[code]](https://github.com/utkarshojha/few-shot-gan-adaptation)
+ Jiayu Xiao, Liang Li, Chaofei Wang, Zheng-Jun Zha, Qingming Huang: "*Few Shot Generative Model Adaption via Relaxed Spatial Structural Alignment.*" CVPR (2022) [[pdf]](https://arxiv.org/pdf/2203.04121.pdf) [[code]](https://github.com/StevenShaw1999/RSSA)
+ Yunqing Zhao, Henghui Ding, Houjing Huang, Ngai-Man Cheung: "*A Closer Look at Few-shot Image Generation.*" CVPR (2022) [[pdf]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhao_A_Closer_Look_at_Few-Shot_Image_Generation_CVPR_2022_paper.pdf) 
+ Xingzhong Hou, Boxiao Liu, Shuai Zhang, Lulin Shi, Zite Jiang, Haihang You: "*Dynamic Weighted Semantic Correspondence for Few-Shot Image Generative Adaptation.*" ACM MM (2022) [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3503161.3548270)
+ JingYuan Zhu, Huimin Ma, Jiansheng Chen, Jian Yuan: "*Few-shot Image Generation via Masked Discrimination.*" arXiv (2022) [[pdf]](https://arxiv.org/pdf/2210.15194.pdf) 

**Datasets:** Sometimes a subset of a dataset is used as the target dataset.
+ ImageNet: Over 1.4M images of 1k categories. [[link]](https://www.image-net.org/index.php)
+ FFHQ (Flickr Faces HQ Dataset): 70k 1024\*1024 face images proposed by NVIDIA in StyleGAN papers. [[link]](https://github.com/NVlabs/ffhq-dataset)
+ Danbooru: Anime image dataset series. The latest version (2021) contains 4.9M images annotated with 162M tags. [[link]](https://www.gwern.net/Danbooru2021)
+ AFHQ (Animal Faces HQ Dataset): 15k 512\*512 animal images of three categories cat, dog and wildlife. [[link]](https://github.com/clovaai/stargan-v2/blob/master/README.md#animal-faces-hq-dataset-afhq)
+ Artistic-Faces Dataset: 160 artistic portraits of 16 artists. [[link]](https://faculty.idc.ac.il/arik/site/foa/artistic-faces-dataset.asp)
+ LSUN: 1M images for each of 10 scene categories and 20 object categories. [[link]](https://www.yf.io/p/lsun)
+ CelebA: 203k face images of 10k identities. [[link]](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)

## Only Small Dataset

The generative model is directly trained on a small dataset. 

+ Shengyu Zhao, Zhijian Liu, Ji Lin, Jun-Yan Zhu, Song Han: "*Differentiable Augmentation for Data-Efficient GAN Training.*" NeurIPS (2020). [[pdf]](https://arxiv.org/pdf/2006.10738.pdf) [[code]](https://github.com/mit-han-lab/data-efficient-gans)
+ Bingchen Liu, Yizhe Zhu, Kunpeng Song, Ahmed Elgammal: "*Towards Faster and Stabilized GAN Training for High-fidelity Few-shot Image Synthesis.*" ICLR (2021).               [[pdf]](https://arxiv.org/pdf/2101.04775v1.pdf) [[code]](https://github.com/odegeasslbc/FastGAN-pytorch)
+ Mengyu Dai, Haibin Hang, Xiaoyang Guo: "*Adaptive Feature Interpolation for Low-Shot Image Generation.*" ECCV (2022). [[pdf]](https://arxiv.org/pdf/2112.02450.pdf)

In the extreme case, the generative model is directly trained on a single image. However, the learnt model generally only manipulates the repeated patterns in this image. 

+ Tamar Rott Shaham, Tali Dekel, Tomer Michaeli: "*SinGAN: Learning a Generative Model from a Single Natural Image.*" ICCV (2019). [[pdf]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Shaham_SinGAN_Learning_a_Generative_Model_From_a_Single_Natural_Image_ICCV_2019_paper.pdf) [[code]](https://github.com/tamarott/SinGAN)
+ Vadim Sushko, Jurgen Gall, Anna Khoreva: "*One-Shot GAN: Learning to Generate Samples from Single Images and Videos.*" CVPR workshop (2021). [[pdf]](https://openaccess.thecvf.com/content/CVPR2021W/LLID/papers/Sushko_One-Shot_GAN_Learning_To_Generate_Samples_From_Single_Images_and_CVPRW_2021_paper.pdf)


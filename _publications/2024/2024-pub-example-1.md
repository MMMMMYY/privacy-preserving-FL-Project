---
title:          "AgrEvader: Poisoning membership inference against Byzantine-robust federated learning"
date:           2024-07-30
selected:       true
pub:            "ACM International Conference on Information and Knowledge Management (CIKM)"
pub_date:       "2024"
abstract: >-
  Generative Adversarial Networks (GANs), as a cornerstone of artificial intelligence (AI), are widely recognized as the intellectual property (IP) of their owners, given the sensitivity of the training data and the commercial value tied to the models. Model extraction attacks, which aim to steal well-trained proprietary models, pose a significant threat to model IP. Nevertheless, current research predominately focuses on the context of machine learning as a service (MLaaS), where the emphasis lies in understanding the attack knowledge acquired through black-box API queries. This restricted perspective exposes a critical gap in investigating model extraction attacks within realistic distributed settings for generative tasks. In this work, we present the first investigation into model extraction attacks against GANs in distributed settings. We provide a comprehensive attack taxonomy, considering three different levels of knowledge the adversary can obtain in practice. Based on it, we introduce a novel model extraction attack named MoEx, which focuses on the GAN-based distributed learning scenario, i.e., Multi-Discriminator GANs, a typical asymmetric distributed setting. MoEx uses the objective function simulation, leveraging data exchanged during the learning process, to approximate the GAN generator owned by the server. We define two attack goals for MoEx, fidelity extraction and accuracy extraction. Then we comprehensively evaluate the effectiveness of MoEx's two goals with real-world datasets. Our results demonstrate its robust capabilities in extracting generators with high fidelity and accuracy compared with existing methods. 
  # cover:          assets/images/covers/cover1.jpg
authors:
- Mengyao Ma
- Shuofeng Liu
- Mahawaga Arachchige Pathum Chamikara
- Mohan Baruwal Chhetri
- Guangdong Bai
# links:
  Paper: https://dl.acm.org/doi/abs/10.1145/3543507.3583542
---
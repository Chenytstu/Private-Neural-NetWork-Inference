
# Machine learning privacy computing framework  [![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Chenytstu/Private-Neural-NetWork-Inference)
> Machine learning privacy computing framework collation
We will update field related papers and codes from time to time!

## FudanMPL  
[!FudanMPL](https://img-blog.csdnimg.cn/img_convert/4752481590b7d49c50a30883312f3bd7.png)
- FudanMPL是由复旦大学 Daslab 实验室韩伟力教授及其学生独立研发的开源安全多方学习平台，是国内首个基于 BGW [17]协议的开源安全多方学习框架。同时该框架作为国内首个发表在安全四大顶会(S&P 和 CCS)上的用于多方训练的创新安全框架，可以用于金融风控、 智慧医疗等隐私敏感场景。平台子项目 SecMML 和 pMPL 得到系统安全领域国际顶尖会议同行专家的认可。截止至 2022 年 11 月 18 日，该项目在 Github 上收获了 82 Stars。 

- 在安全模型以及应用层方面，相较于已有的安全多方学习框架，FudanMPL 基于 Shamir 秘密共享、支持更加丰富的应用场景（数据横向、纵向分割，特权方与辅助方协作，多方机器学习模型安全训练与推理），其中，SecMML 子项目能够支持诚实大多数的半诚实安全三方及以上的训练和推理，pMPL子项目主要基于向量秘密共享协议，支持诚实大多数的半诚实安全三方的训练与推理，SecureKVM 子项目能够支持诚实大多数的半诚实安全场景下 的多方机器学习安全训练与推理，verticalMPL 子项目能够支持诚实大多数的半诚实安全场景下的数据纵向分割。从技术路线角度，FudanMPL 支持秘密分享，技术路线相对单一，但 在秘密分享技术中，FudanMPL 支持 Shamir 秘密共享以及向量秘密共享，其中向量秘密共享是 FudanMPL 独有的为特权参与方场景所实现的秘密分享方式。在易用性方面，FudanMPL 代码结构清晰，维护了相对完备的文档，进而大大提高了该框架的易用性。


- 2023-TIFS-FastSecNet: An Efficient Cryptographic Framework for Private Neural Network Inference
  [[paper]](https://ieeexplore.ieee.org/abstract/document/10081492/metrics#metrics)

## Private-Neural Network Train
- 2022-TNSE- SecureTrain: An Approximation-Free and Computationally Efficient Framework for Privacy-Preserved Neural Network Training.
  [[paper]](https://ieeexplore.ieee.org/document/9271910#:~:text=SecureTrain%20enables%20joint%20linear%20and%20nonlinear%20computation%20based,to%20achieve%20training%20stability%20and%20prevent%20accuracy%20loss.)
  [[code]](https://github.com/ChiaoThon/SecureTrain)

## Contribute

Contributions are always welcome!


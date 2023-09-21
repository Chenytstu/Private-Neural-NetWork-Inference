
# Machine learning privacy computing framework  [![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Chenytstu/Private-Neural-NetWork-Inference)
> Machine learning privacy computing framework collation
We will update field related papers and codes from time to time!

## FudanMPL  
<div align=center>
<img src="https://github.com/Chenytstu/Private-Neural-NetWork-Inference/assets/80495405/5e405352-1483-41f2-abe9-2cfccb623780" >
</div>

- FudanMPL[[Link]](https://github.com/FudanMPL)是由复旦大学 Daslab 实验室韩伟力教授及其学生独立研发的开源安全多方学习平台，是国内首个基于 BGW [17]协议的开源安全多方学习框架。同时该框架作为国内首个发表在安全四大顶会(S&P 和 CCS)上的用于多方训练的创新安全框架，可以用于金融风控、 智慧医疗等隐私敏感场景。平台子项目 SecMML 和 pMPL 得到系统安全领域国际顶尖会议同行专家的认可。截止至 2022 年 11 月 18 日，该项目在 Github 上收获了 82 Stars。 

- 在安全模型以及应用层方面，相较于已有的安全多方学习框架，FudanMPL 基于 Shamir 秘密共享、支持更加丰富的应用场景（数据横向、纵向分割，特权方与辅助方协作，多方机器学习模型安全训练与推理），其中，SecMML 子项目能够支持诚实大多数的半诚实安全三方及以上的训练和推理，pMPL子项目主要基于向量秘密共享协议，支持诚实大多数的半诚实安全三方的训练与推理，SecureKVM 子项目能够支持诚实大多数的半诚实安全场景下 的多方机器学习安全训练与推理，verticalMPL 子项目能够支持诚实大多数的半诚实安全场景下的数据纵向分割。从技术路线角度，FudanMPL 支持秘密分享，技术路线相对单一，但 在秘密分享技术中，FudanMPL 支持 Shamir 秘密共享以及向量秘密共享，其中向量秘密共享是 FudanMPL 独有的为特权参与方场景所实现的秘密分享方式。在易用性方面，FudanMPL 代码结构清晰，维护了相对完备的文档，进而大大提高了该框架的易用性。



## Primihub
<div align=center>
<img src="https://github.com/Chenytstu/Private-Neural-NetWork-Inference/assets/80495405/bea3701f-29db-41c7-8a7e-e763fae0860c" >
</div>

- Primihub[[Link]](https://github.com/primihub/primihub)是由原语科技研发的开源可信隐私计算平台，该平台融合了安全多方计算 (MPC)、联邦学习(FL)、同态加密(HE)、可信执行环境(TEE)等多种隐私计算技术，并提供多安全级别、多性能要求、多场景下的应用。是国内技术方案较为齐全的隐私计算平台之一，截止至 2022 年 11 月 12 日，该项目在 Github 上收获了 253 Stars。在本文中，将主要针对该框架的安全多方计算技术板块进行评估分析。

- 在安全模型方面，Primihub 主要集成了安全多方计算协议 ABY3 [2] , ABY2.0 [16], Cheetah [5]， Falcon [13]以及 cryptFlow2 [9]。其中 ABY3 能够支持诚实大多数的半诚实安全三方训练协议， ABY2.0 能够支持诚实大多数的半诚实安全两方训练协议，Cheetah 能够支持诚实大多数的 半诚实安全两方推理协议，Falcon 能够支持诚实大多数的恶意三方安全训练及预测协议， cryptFlow2 能够支持半诚实的两方安全预测协议。从技术路线角度，Primihub 支持同态加密， 秘密分享以及不经意传输，技术路线完备。同时，从应用层角度来看，Primihub 在安全多方学习的应用场景方面复杂多样，支持隐私保护求交，线性回归，逻辑回归，XGBoost 以及神经网络，模型支持数量多且完备。

- 在易用性方面，Primihub 代码结构清晰，维护了相对完备的文档（https://docs.primihub.com/docs/quick-start），同时在各平台进行讲解推广，进而大大提高了该框架的易用性。在特定优化方面，Primihub 针对支持 SSE2 extensions 的处理器提供了一些指令优化以提升计算速度，该优化主要针对移位操作。


## EzPC
<div align=center>
<img src="https://github.com/Chenytstu/Private-Neural-NetWork-Inference/assets/80495405/4b2d8077-fdd3-4d25-ab01-60c7cb2d75a7" >
</div>

- EzPC[[Link]](https://github.com/mpc-msri/EzPC)是微软开源的安全多方学习框架，该框架主要支持安全多方计算(MPC)这一隐私计算技术，针对安全推理场景提供了相对完备的安全级别定义，相关研究工作自成一体，是安全多方学习框架中安全推理场景的标杆之一，该框架在安全推理领域得到系统安全领域国际顶尖会议同行专家的认可[18][19][20][21]。截止至 2022 年 11 月 12 日，该项目在 Github 上收获了 268 Stars。

- 在安全模型方面，EzPC 主要针对半诚实场景[8][9]。从技术路线角度来看，EzPC 支持秘密分享，不经意传输以及同态加密技术路线相对完备。从应用层的这项指标进行分析，EzPC 目前主要是针对安全推理场景设计，因此应用层主要是对神经网络进行支持。

- 在易用性与针对性优化方面，EzPC 是首个实现算术秘密分享和布尔秘密分享混合运算的框架，该框架向用户隐藏了底层密码学原语，根据所需计算自动进行算术秘密分享以及布尔秘密分享的转换，例如，在进行矩阵乘法时使用算术秘密分享，进行位运算时自动转为布尔秘密分享，用户无需手动进行转换，因此大幅度提高了该框架的易用性。同时针对性的转换也提高了框架的运行效率，Nishanth 等人在 2019 年发表的文章[10]中指出 EzPC 在各种场景至少与其他框架效率保持一致，最好时甚至能够快 19 倍。



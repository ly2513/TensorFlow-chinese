这里主要是整理关于`TensorFlow`的一些资料,中文版的,希望对大家有所帮助。

包含一些很棒的 TensorFlow 工程、库、项目等。

> 什么是TensorFlow？

TensorFlow 是一个采用数据流图（data flow graphs），用于数值计算的开源软件库。节点（Nodes）在图中表示数学操作，图中的线（edges）则表示在节点间相互联系的多维数据数组，即张量（tensor）。它灵活的架构让你可以在多种平台上展开计算，例如台式计算机中的一个或多个CPU（或GPU）、服务器、移动设备等等。TensorFlow 最初由Google Brain 小组（隶属于Google机器智能研究机构）的研究员和工程师们开发出来，用于机器学习和深度神经网络方面的研究，但这个系统的通用性使其也可广泛用于其他计算领域。

> 教程

+ TensorFlow 教程1 – 从基础到有趣的TensorFlow程序
+ TensorFlow 教程2 – 介绍基于谷歌TensorFlow框架的深度学习，其中有些教程是学习了Newmu的Theano教程
+ TensorFlow 实例 – TensorFlow教程以及一些新手的代码实例
+ Sungjoon的TensorFlow-101 – 在Jupyter Notebook上用python写的TensorFlow教程
+ Terry Um的TensorFlow练习 – 根据其他TensorFlow项目再创作的代码
+ 在树莓派3上安装TensorFlow – 在树莓派上正确安装和运行TensorFlow
+ 时间序列上的分类 – 在TensorFlow上的基于手机传感数据的LSTM循环神经网络

> 模型/工程

+ 图片形态转换 – 无监督图片形态转换的实现
+ Show, Attend and Tell算法 -基于聚焦机制的自动图像生成器
+ Neural Style – Neural Style 算法的TensorFlow实现
+ Pretty Tensor – Pretty Tensor提供了高级别的TensorFlow封装接口
+ Neural Style – neural style的又一实现
+ AlexNet3D – 用3D卷积层实现AlexNet
+ TensorFlow笔记 – TensorFlow的学习笔记和总结，附带一些图片说明
+ NeuralArt – 艺术风格绘画的神经网络算法TensorFlow实现
+ DQN玩乒乓
+ TensorFlow生成手写体 – 实现Alex Grave的论文中关于生成手写体的部分
+ TensorFlow实现神经图灵机 – TensorFlow实现神经图灵机
+ 基于物体搜索和过滤视频 – 使用卷积神经网络基于视频中的物品、地点等来搜索、过滤和描述视频
+ 使用TensorFlow来转换莎士比亚作品和现代版本的英语 – 实现莎士比亚作品和现代版本的英语的单语转换
+ 聊天机器人 – 一个基于深度学习的聊天机器人
+ colornet – 使用神经网络给灰度图像着色
+ 图像生成器 – Show and Tell算法实现
+ Attention based的自动图像生成器 – Show, Attend and Tell算法实现
+ Weakly_detector – 用于定位的深度特征
+ Dynamic Capacity Networks – DCN的TensorFlow实现
+ TensorFlow实现HMM – 实现HMM的维特比算法和前后向算法
+ DeepOSM – 使用OpenStreetMap和卫星图像训练深度学习网络
+ DQN-tensorflow – TensorFlow通过OpenAI Gym实现深度学习来实现“深度强化学习下达到人类水平的控制”
+ Highway Networks – 使用TensorFlow和Fomoro进行简单的超深度网络训练
+ 用CNN做句子分类 – 用TensorFlow实现句子分类的卷积神经网络
+ End-To-End Memory Networks – 使用TensorFlow实现End-To-End的Memory Network
+ Character-Aware的神经语言模型 – 基于字符感知的LSTM语言模型
+ YOLO TensorFlow ++ – TensorFlow实现YOLO实时物体检测，支持实时运行在移动设备上
+ Wavenet – TensorFlow实现用来生成音频的WaveNet对抗生成网络架构
+ Mnemonic Descent Method – TensorFlow实现助记符下降法：重现端对端的人脸对齐

>由TensorFlow提供技术支持

+ YOLO TensorFlow – 实现YOLO:实时物体检测
+ android-yolo – 在安卓设备商使用YOLO实行实时物体检测，由TensorFlow提供技术支持
+ Magenta – 在制作音乐和艺术中使用机器智能提升艺术形态（研究项目）

> 库

+ Scikit Flow (TensorFlow Learn) – 深度/机器学习的简化版接口（现在是TensorFlow的一部分）
+ tensorflow.rb – TensorFlow的Ruby版本，使用了SWIG
+ TensorFlowlearn – 有高级别API的深度学习库
+ TensorFlow-Slim – TensorFlow中的高级别简化版库
+ TensorFrames – Apache Spark上DataFrames的TensorFlow封装
+ caffe-tensorflow – 转换Caffe模型为TensorFlow的模式
+ keras – 用于TensorFlow和Theano的小型的模块化的库
+ SyntaxNet 语法分析神经网络模型 – 全球标准化的Transition-Based神经网络模型的TensorFlow实现
+ keras-js – 在GPU的支持下，在浏览器中运行Keras模型
+ NNFlow – 一个简单的框架，可以将ROOT NTuples转换成可以在TensorFlow使用的Numpy数据

> 视频

+ TensorFlow Guide 1 – TensorFlow的安装和使用指南1
+ TensorFlow Guide 2 – TensorFlow的安装和使用指南2
+ TensorFlow Basic Usage – 基本使用指南
+ TensorFlow Deep MNIST for Experts – 深入了解MNIST
+ TensorFlow Udacity Deep Learning – 在有1GB数据的Cloud 9在线服务安装TensorFlow的步骤
+ 为什么谷歌希望所有人都可以访问TensorFlow
+ 1/19/2016TensorFlow 硅谷见面会
+ 1/21/2016TensorFlow 硅谷见面会
+ 19th Apr 2016 斯坦福CS224d 第七课 – TensorFlow介绍 – CS224d 用于自然语言处理的深度学习 By Richard Socher
+ 通过TensorFlow了解机器学习 – Pycon 大会，2016年
+ 使用TensorFlow的大规模深度学习 – Jeff Dean在Spark Summit 2016上的演讲
+ TensorFlow和深度学习

> 论文

+ TensorFlow: Large-Scale Machine Learning on Heterogeneous Distributed Systems – 论文介绍了TensorFlow的接口以及我们在google上构建的这些接口的实现
+ TensorFlow.Learn: TensorFlow’s High-level Module for Distributed Machine Learning – TensorFlow用于分布式机器学习的高级别模块
+ Comparative Study of Deep Learning Software Frameworks – 这个研究运行在不同的深度学习架构上，我们也评估在单机上使用CPU和GPU配置时同一框架的性能
+ Distributed TensorFlow with MPI – 在论文中，我们使用MPI将TensorFlow在大规模集群中扩展
+ Globally Normalized Transition-Based Neural Networks – 这个论文介绍了SyntaxNet背后的模型
+ TensorFlow: A system for large-scale machine learning – 这个论文展示了TensorFlow的数据流模型并与存在的系统进行对比，展现了它引人注目的性能

> 官方公告

+ TensorFlow: smarter machine learning, for everyone – 介绍了TensorFlow
+ Announcing SyntaxNet: The World’s Most Accurate Parser Goes Open Source – SyntaxNet的发布公告“一个基于TensorFlow的开源神经网络系统，为自然语言理解系统打下了基础”


> 博文

+ Why TensorFlow will change the Game for AI – 为什么TensorFlow会改变游戏的AI
+ TensorFlow for Poets – 了解TensorFlow的实现
+ Introduction to Scikit Flow – Simplified Interface to TensorFlow – Scikit Flow简介，它简化了TensorFlow的接口
+ Building Machine Learning Estimator in TensorFlow – 了解TensorFlow的内部学习评估器
+ TensorFlow – Not Just For Deep Learning – TensorFlow,不仅仅为了深度学习
+ The indico Machine Learning Team’s take on TensorFlow – indico机器学习团队采纳TensorFlow
+ The Good, Bad, & Ugly of TensorFlow – 为期六个月快速演进的报告（一个小贴士和窍门来弥补TensorFlow的不足）
+ Fizz Buzz in TensorFlow – Joel Grus的一个玩笑
+ RNNs In TensorFlow, A Practical Guide And Undocumented Features – 基于TensorFlow的RNN实现，Github上提供了步骤和全套代码
+ 使用TensorBoard来可视化TensorFlow训练的图片分类
+ TensorFlowRecords Guide – 语义分割和处理TensorFlowRecord文件格式

> 社区

+ Stack Overflow
+ @TensorFlo on Twitter
+ Reddit
+ Mailing List

> 书

+ 《First Contact with TensorFlow – 第一次接触TensorFlow》。作者 Jordi Torres 是UPC Barcelona Tech 的教授。也是 Barcelona 超级计算中心的研究经理和高级顾问
+ 《Deep Learning with Python – 深度学习之python》，使用Keras在Theano和TensorFlow开发深度学习模型
+ 《TensorFlow for Machine Intelligence – TensorFlow实现机器智能》，提供完成的教程，从基本的图运算到在实际应用中制造深度学习模型
+ 《Getting Started with TensorFlow – TensorFlow入门》，开始学习并使用谷歌最新的数据计算库TensorFlow来深度分析数据
+ 《Hands-On Machine Learning with Scikit-Learn and TensorFlow – 通过Scikit-Learn和TensorFlow来实践机器学习》，覆盖了机器学习的基础、训练以及在多个服务器和GPU上部署深度学习网络，以及CNN、RNN、自动编码器和Deep Q.
+ 《Building Machine Learning Projects with Tensorflow》 – 这本书包含了多个不同类型的工程，来说明TensorFlow在不同场景中的应用，这本书的工程包括了训练模型、机器学习、深度学习以及多种神经网络，每个工程都是一个精妙的、有意义的项目，会教我们如何使用TensorFlow并在使用中如何对数据分层
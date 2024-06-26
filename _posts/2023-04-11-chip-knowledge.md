---
layout: post
title: 芯片制造的知识
categories: Chip
description: 芯片制造的知识
keywords: chip
---

# 芯片制造的知识

## 一、微芯片的基础知识

*关于微芯片您需要了解的一切——数字世界的基础*

*技术的基石：很难想象一个没有微芯片的世界。它们是我们用来工作、旅行、健身和娱乐的设备的核心装置——从汽车到智能手机，从核磁共振扫描仪到工业机器人以及数据中心。*

*微芯片无处不在。2021年，半导体单位销售额达到创纪录的1.15万亿单位出货量，2022年，全球半导体行业销售额突破573.5欧元。通过每一代产品都提供新的功能、更好的性能和更低的成本，芯片的进步催生了新产品并改变了行业。*

![image](https://github.com/weakchen007/aiwv.github.io/assets/58799395/d9f0d106-e1ea-4a96-a7c6-d494a61ab26c)

### 1、什么是微芯片？

微型芯片（又称芯片、计算机芯片、集成电路或集成电路）是在一小块平面硅片上的一组电子电路。在芯片上，晶体管充当微型电子开关，可以接通或断开电流。微小开关的图案是通过添加和去除材料在硅片上形成的，从而形成相互连接的多层晶格。

![image](https://github.com/weakchen007/aiwv.github.io/assets/58799395/edb90c98-41f1-470e-afae-e410c7069dfd)

### 2、数字黄金

硅是芯片工业的首选材料。与通常用于传导电流的金属不同，硅是一种 "半导体"，这意味着通过与磷或硼等其他材料混合，可以提高其导电性能。这就使得开启或关闭电流成为可能。

好消息是，硅无处不在！硅由沙子制成，是地球上含量仅次于氧气的元素。硅晶片是用一种叫做硅砂的沙子制成的，硅砂是由二氧化硅制成的。硅砂熔化后铸成一个大圆柱体，称为 "硅锭"。然后将硅锭切成薄片。

![image](https://github.com/weakchen007/aiwv.github.io/assets/58799395/0cf19f4f-d03f-4802-97d9-b91f639f94c6)

### 3、纳米级

指甲盖大小的微型芯片包含数十亿个晶体管，因此很容易理解芯片上的特征需要有多小。芯片特征以纳米为单位。纳米是十亿分之一米，或百万分之一毫米。

相比之下，人类红细胞的直径为7000纳米，流感病毒的直径约为100纳米。最先进的微芯片包含的功能只有几十纳米大小。ASML的EUV（极紫外）技术可以进一步缩小最小特征的尺寸。我们的系统能够创建的图案特征越小，制造商就能在芯片上安装越多的晶体管，芯片的功能也就越强。

![image](https://github.com/weakchen007/aiwv.github.io/assets/58799395/59541be0-191c-484c-9000-6751cb1c8580)

### 4、芯片的“口味”

对微型芯片的分类主要有两种方法：按功能和按集成电路类型。就电路而言，芯片可以是模拟的、数字的或混合的。模拟功能和数字功能的区别在于它们处理的电信号不同。在数字芯片中，信号是二进制的。在模拟芯片中，信号是连续的，这意味着它们可以在给定范围内取任何值，而且它们使用更传统的电路元件（电阻器、电容器，有时还有电感器）。

就功能而言，可分为四大类： 逻辑芯片、存储芯片、特定应用集成芯片（ASIC）和片上系统设备（SoC）。逻辑芯片和存储芯片这两类最常见的芯片都是数字芯片：它们使用晶体管操作和存储比特和字节。ASIC和SoC主要是模拟和数字的混合体。

#### （1） 逻辑芯片

逻辑芯片是电子设备的 "大脑"--它们处理信息以完成任务。在逻辑芯片中，CPU（中央处理器）是 "原始 "芯片，最早设计于20世纪60年代。但也有一些处理器具有特定功能，如GPU（图形处理单元，针对视觉显示进行了优化）和NPU（神经处理单元，针对深度学习和机器学习应用而设计）。

#### （2）内存芯片

内存芯片存储信息。内存有两种类型：易失性和非易失性。易失性内存芯片，如 DRAM（动态随机存取存储器），是 "工作内存 "芯片，仅在设备电源打开时保存数据。非易失性内存芯片（如 NAND 闪存）即使在设备关机后也能保存数据。例如，DRAM 可帮助在设备上运行程序，而 NAND 则可存储照片。DRAM 读取和写入数据的速度较快，而 NAND 读取和写入数据的速度较慢。

#### （3）ASICs

ASIC 是一种简单的单用途芯片，用于执行扫描条形码等重复性处理程序。

#### （4）SoCs

SoC本质上是集成芯片。它们是一种相对较新的芯片类型，在单个芯片中集成了许多芯片和电路，可集成图形、音频、摄像头、视频和Wi-Fi等功能。

### 5、计算能力

计算能力和内存功能的惊人增长是芯片改进的结果，正是芯片的改进使技术发展到今天的水平。1956年至2015年，计算能力增长了一万亿倍，这要归功于芯片。试想一下：为阿波罗登月任务导航的计算机的计算能力大约是任天堂游戏机的两倍。它拥有32.768位随机存取存储器（RAM）和589.824位只读存储器（ROM）。现代智能手机的处理能力大约是它的10万倍，RAM和ROM分别是它的100万倍和700万倍。

芯片支持虚拟现实和设备上人工智能（AI）等应用，并提高了数据传输（如5G连接）的效率，同时还支持深度学习等算法。

所有这些计算都会产生大量数据。到 2025 年，全球每年将产生175 ZB的数据，大约相当于10亿TB。相比之下，根据市场情报公司IDC的"2025 数据时代"白皮书，如果将175 ZB的数据存储在DVD上，那么这堆DVD的高度足以绕地球222圈。

![image](https://github.com/weakchen007/aiwv.github.io/assets/58799395/3cb63d18-f8cb-41bf-b61f-39f54fa914b7)

## 二、如何制造微芯片

微型芯片是通过在硅晶片上建立一层层相互连接的图案而制成的。

微芯片制造过程涉及数百个步骤，从设计到批量生产可能需要长达四个月的时间。在芯片制造商晶圆厂（制造工厂）的洁净室里，空气质量和温度受到严格控制，机器人将珍贵的晶片从一台机器运送到另一台机器。

芯片制作的步骤：

### 步骤一 沉积：

制造微芯片的第一步通常是将材料薄膜沉积到硅水。这些材料可以是导体、绝缘体或半导体。

### 步骤二 光刻：

光刻，或称照相平版印刷，是计算机芯片制造过程中的关键步骤。它包括在晶片上涂上光敏材料，然后在光刻机内进行曝光。

### 步骤三 光刻涂胶层：

要打印芯片层，首先要在晶片上涂一层感光层，称为 "光刻胶"，简称 "抗蚀剂"。然后进入光刻机。

### 步骤四 曝光：

在光刻机内部，光线通过包含要印刷图案蓝图的网罩投射到水面上。系统的光学器件缩小并将图案聚焦到抗蚀剂上。在光照射到抗蚀剂的地方，它会引起化学变化，从而从抗蚀剂的网状结构中再现图案。

### 步骤五 计算光刻：

包含要在晶片上印刷的图案的网罩有时需要通过故意使图案变形来优化，以补偿光刻过程中发生的物理和化学效应。光刻机通过将算法模型与来自我们机器和测试晶圆的数据相结合来实现这一目标。

### 步骤六 烘烤和显影：

离开光刻机后，晶圆将被烘烤并显影以使这些变化永久化，并且一些光致抗蚀剂被洗掉以在抗蚀剂中形成开放空间的图案。

### 步骤七 刻蚀：

气体等材料用于从开发阶段产生的开放空间中蚀刻掉材料，留下图案的3D版本。

### 步骤八 金属化及检查：

在整个芯片生产过程中，都要对晶片进行测量并检查是否存在误差。这些测量结果会反馈到系统中，用于优化和稳定设备。

### 步骤九 离子注入：

在去除剩余的光刻胶之前，还可以用正离子或负离子轰击晶片，以调整图案部分的半导体特性。

### 步骤十 按需要重复

从沉积到去除抗蚀剂，整个过程不断重复，直到晶片上布满图案，完成一层晶片。要制作整个芯片，这一过程可重复多达 100 次，在图案上再叠加图案，以创建集成电路。

### 步骤十一 加工后的芯片

在生产的最后一步，晶圆被切成单独的芯片，然后封装在保护性封装中。该芯片现已准备好用于电视、平板电脑或其他数字设备。

### 1、微小的摩天大楼

现代芯片可以有多达 100 层，所有这些层都需要以纳米级的精度相互对齐（称为 "叠加"）。芯片上印刷的特征尺寸因层而异，这意味着不同层需要使用不同类型的光刻系统。我们最新一代的 EUV（极紫外）设备用于具有最小特征的最关键层，而DUV（深紫外）设备则用于具有较大特征的不太关键层。

![image](https://github.com/weakchen007/aiwv.github.io/assets/58799395/2a9cf66b-f92e-4df8-82f0-f0c7eb9f9cd4)

### 2、多干净才算“干净”？

如果晶片上出现哪怕一丁点灰尘或其他异物，都会毁掉芯片，因此芯片制造商都会小心翼翼地保持晶圆厂的清洁。到底有多干净？比外面的空气洁净一万倍。大多数芯片制造商都拥有“零粉尘”的“ISO 1级”洁净室，这意味着每立方米空气中大小在100纳米到200纳米之间的颗粒不超过10个，大于200纳米的颗粒一个都没有。相比之下，现代洁净医院每立方米的空气中约有10,000个尘埃粒子。

无尘室内的空气经过过滤并不断循环，员工穿着特殊的服装（有时称为 "兔子服"），以帮助保持空气中无微粒。

![image](https://github.com/weakchen007/aiwv.github.io/assets/58799395/a25666a3-ea7f-436f-aa95-a643a0a41bb8)

### 3、芯片制造商的类型

集成设备制造商（IDM），如英特尔和三星，既设计也制造芯片。而代工厂则是根据合同为其他公司制造芯片的公司。台积电、GLOBALFOUNDRIES和联电就是这类芯片制造商的代表。第三类芯片制造商是“无晶圆厂半导体公司”，如高通（Qualcomm）、英伟达（Nvidia）和AMD，它们只专注于芯片设计，避免了建设和维护生产设施的高昂成本。这些公司可能会将生产外包给代工厂。


-----------



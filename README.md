# ICDAR2019-ReCTS
`enhence_pic.py`采用旋转、亮度调整、仿射变换等对图像做数据增强，`divide_train_test.py`对训练集、测试集进行划分，`alexnet_0509.py`是最终训练和输出结果的核心部分，需要将结果输出为图片名、识别结果的txt格式。

<h3>比赛结果</h3>

![Example image2](https://github.com/HuiyanWen/ICDAR2019-ReCTS/blob/master/1.png)  

<h3>心得#2019.06更新#</h3>
<br>其实这次比赛仅仅是复现了经典网络，并没有过多做优化，但可以看到，已经超过了北航、川大等校。这一个月我在网络优化方面取得了一定突破，能在原来基础上提高0.5-2.0个百分点，已接近腾讯、阿里等顶级公司的商用要求(完全追上或赶超很难，毕竟没有那么多数据)。具体思路和源码可以参考[我的毕业论文](https://github.com/HuiyanWen/bysj_hit)，获得了哈工大百优毕业设计，目前正在撰写论文。</br>

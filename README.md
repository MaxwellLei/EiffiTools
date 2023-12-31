# 说明

软件的初衷是始于课题组中一位朋友的需求开始（当然项目的相关功能会偏向于地质学，矿业工程，勘察等相关和一般的研究生及其以上的一些可能需要的功能出发），然后打算做成相关工具，目前已经实现的功能：

* **Mapping（元素分布测量）数据重排列**：获得的元素分布测量数据，导入 Origin 中作图数据为了符合相关需求，对数据重排列以满足数据格式要求。
* **数据收集管理**：当你有相关大数据需求，需要从大量的论文中查找并收集和统计数据，在各个数据库和相关网站的时候统计自己从各个地方收集的数据相当麻烦，手工查找计数更是难上加难，**古人云：工欲善其事，必先利其器**。对于数据的管理就必不可少，该功能提供了一些必要的帮助。

**其他功能还在开发中**

* **表格提取**：尝试提供一种 PDF 提取数据的解决方案
* **论文信息查询**：快速查询论文的相关分区和影响因子等信息
* **论文下载**：提供论文下载的方式
* **论文润色**：看看吧，借助 GPT 来润色论文
* **定时提醒**：定时提醒您的相关事宜，例如：休息提醒
* **CAJ 转 PDF**：FUCK CAJ

遂我打算开发这个软件不止来帮助我，更是帮助更多有这方面需求的人员。

当然，如果你在使用过程中遇到任何问题，可以在项目中或者私信我进行反馈。

# 关于软件

软件使用 WPF 开发技术，基于 MVVM 架构，仅在 Windows 平台有效，考虑到 MAUI 的不稳定性，所以并不考虑跨平台的问题。

> 项目基于 MIT 协议，可以任意使用并二次开发。
![cover](https://github.com/Sophomoresty/typora-scu-eassy-theme/blob/master/img/cover.png?raw=true)
# 红色学术风SCU主题

[下载与安装](#下载与安装) | [论文封面修改](#论文封面修改) | [scu-essay格式总览](#scu-essay格式总览) <br/>

本项目一共提供两个Typora主题，均为浅色主题。<br/>
在 windows 上设计和测试。未经全面测试，但应该适用于 macos/Linux。

| scu-essay                                              | scu                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| 以[latex主题](https://github.com/Keldos-Li/typora-latex-theme)为模板，参考`四川大学本科毕业论文（设计）格式和参考文献著录要求`，从好看的角度优化过字体和行间距，**并未严格遵守要求**，但能够满足大部分**中国大陆本科生**的**课程论文**需求。<br/>该模板适合课程论文的书写，不建议日用。 | 参考了lapis模板，采用川大锦绣红风格。<br />该模板适合日常使用 |
| ![theme-scu-essay.png](https://github.com/Sophomoresty/typora-scu-eassy-theme/blob/master/img/theme-scu-essay.png?raw=true) | ![theme-scu.png](https://github.com/Sophomoresty/typora-scu-eassy-theme/blob/master/img/theme-scu.png?raw=true) |



## 主题预览

### 封面

| ![封面.png](https://github.com/Sophomoresty/typora-scu-eassy-theme/blob/master/img/%E5%B0%81%E9%9D%A2.png?raw=true) | ![摘要、关键词.png](https://github.com/Sophomoresty/typora-scu-eassy-theme/blob/master/img/%E6%91%98%E8%A6%81%E3%80%81%E5%85%B3%E9%94%AE%E8%AF%8D.png?raw=true) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

#### 层级标题

|                          scu-essay                           |                             scu                              |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![层级标题-scu-essay.png](https://github.com/Sophomoresty/typora-scu-eassy-theme/blob/master/img/%E5%B1%82%E7%BA%A7%E6%A0%87%E9%A2%98-scu-essay.png?raw=true) | ![层级标题-scu.png](https://github.com/Sophomoresty/typora-scu-eassy-theme/blob/master/img/%E5%B1%82%E7%BA%A7%E6%A0%87%E9%A2%98-scu.png?raw=true) |

#### 表格

|                          scu-essay                           |                             scu                              |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![表格-scu-essay.png](https://github.com/Sophomoresty/typora-scu-eassy-theme/blob/master/img/%E8%A1%A8%E6%A0%BC-scu-essay.png?raw=true) | ![表格-scu.png](https://github.com/Sophomoresty/typora-scu-eassy-theme/blob/master/img/%E8%A1%A8%E6%A0%BC-scu.png?raw=true) |

### 项目列表

| scu-essay                                                    | scu                                                          |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![项目列表-scu-essay.png](https://github.com/Sophomoresty/typora-scu-eassy-theme/blob/master/img/%E9%A1%B9%E7%9B%AE%E5%88%97%E8%A1%A8-scu-essay.png?raw=true) | ![项目列表-scu.png](https://github.com/Sophomoresty/typora-scu-eassy-theme/blob/master/img/%E9%A1%B9%E7%9B%AE%E5%88%97%E8%A1%A8-scu.png?raw=true) |

## 引用块

两个主题样式相同

![引用块-scu.png](https://github.com/Sophomoresty/typora-scu-eassy-theme/blob/master/img/%E5%BC%95%E7%94%A8%E5%9D%97-scu.png?raw=true)

### 代码块

| scu-essay                                                    | scu                                                          |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![代码块-scu-essay.png](https://github.com/Sophomoresty/typora-scu-eassy-theme/blob/master/img/%E4%BB%A3%E7%A0%81%E5%9D%97-scu-essay.png?raw=true) | ![代码块-scu.png](https://github.com/Sophomoresty/typora-scu-eassy-theme/blob/master/img/%E4%BB%A3%E7%A0%81%E5%9D%97-scu.png?raw=true) |



## 下载与安装
请完整阅读以下过程，以确保一切符合预期。

Typora 是一个支持实时预览的 markdown 编辑器。在安装本主题前，请确认您已下载 [Typora](https://typoraio.cn/) 并完成了安装。如果您对 markdown 的语法还不了解，您可以从[Typora](https://typoraio.cn/)中获得帮助。

[下载并解压打包好的压缩包](https://github.com/Sophomoresty/typora-scu-eassy-theme/releases/tag/v0.1.0)

### 安装主题
1. 打开`Typora`->文件->偏好设置->外观->打开主题文件夹

2. 复制`scu.css`文件、`scu-essay.css`文件到主题文件夹下

3. 重启`Typora`

4. 打开`Typora`->主题->选择 `scu-essay（论文主题）`或者 `scu（日用主题）`

### 安装字体

进入解压缩后的文件夹，打开`fonts`文件夹，双击字体文件，安装字体，建议全部安装。

**请务必确认您完成了下面的步骤：**
- 安装主题
- 下载并安装所需的字体

## 论文封面修改

封面`cover-templated.md`和示例论文`essay-template.md`在`template`文件夹中。

论文封面使用HTML实现，使用时，替换掉对应的内容即可。

> 如需更换为自己的学校，找到自己学校的校徽、校名的高清图，在[在线转换网站中](https://products.aspose.app/imaging/zh-hans/conversion)将图片转化为SVG，在`cover/essay-template`封面HTML中替换相应的链接即可
>
>![image-20240825031255756.png](https://github.com/Sophomoresty/typora-scu-eassy-theme/blob/master/template/assets/image-20240825031255756.png?raw=true)

## scu-essay格式总览

|         大纲级别          |        英，中字体         | 样式            | 中文字号  | 磅/pt |
| :-----------------------: | :-----------------------: | --------------- | :-------: | :---: |
|         封面标题          | Times New Roman，华文中宋 | 加粗            |   一号    |  26   |
|       封面表格内容        | Times New Roman，思源宋体 | 加粗            |   四号    |  14   |
|        论文总标题         | Times New Roman，华文中宋 | 加粗            | 二号 加粗 |  22   |
|       学校专业姓名        |   Times New Roman，楷体   | 无              |   四号    |  14   |
|        摘要/关键字        |   Times New Roman，楷体   | 加粗            |   小五    |   9   |
|     摘要/关键字的内容     |   Times New Roman，楷体   | 无              |   小五    |   9   |
|        一级标题/h1        | Times New Roman，华文中宋 | 加粗            |   小三    |  15   |
|        二级标题/h2        | Times New Roman，华文中宋 | 加粗            |   四号    |  14   |
|        三级标题/h3        | Times New Roman，华文中宋 | 加粗            |   小四    |  12   |
| 四、五、六级标题/h4,h5,h6 |   Times New Roman，楷体   | 加粗            |   小四    |  12   |
|           正文            | Times New Roman，思源宋体 | 无，行间距1.5倍 |   小四    |  12   |
|         表格标题          |   Times New Roman，楷体   | 加粗            |   小四    |  12   |
|         表格内容          |   Times New Roman，楷体   | 无              |   五号    | 10.5  |
|          引用块           |   Times New Roman，楷体   | 无              |   小四    |  12   |
|      行内代码/代码块      |    Cantarell，思源宋体    | 无              |   小四    |  12   |

### 页边距

上2.5cm，下2.5cm，左2.5cm，右2cm，装订线0

>经过测试，导出不用设置`Typora`的`PDF`页边距。
>
>如需修改页边距，请在主题`CSS`中修改图中的`margin`值，顺序是上、右、下、左，不要删除后面的`! important;`
>举例，如果需要修改页边距为上1cm、下1cm、左2cm、右1.5cm，则应填：`1cm 1.5cm 1cm 2cm`
>
>![image-20240825035038063.png](https://github.com/Sophomoresty/typora-scu-eassy-theme/blob/master/template/assets/image-20240825035038063.png?raw=true)
>

## 鸣谢

本项目是在下面两个开源项目的基础上完成的
- [Keldos-Li/typora-latex-theme](https://github.com/Keldos-Li/typora-latex-theme)
- [YiNNx/typora-theme-lapis](https://github.com/YiNNx/typora-theme-lapis) 


# Style Transfer Online With Onnx Runtime

## Introduction

这个仓库是一个由python flask框架建成的web项目，用户能够在线的尝试风格迁移算法。该项目的推理计算都在前端完成，依赖onnx runtime在前端搭建神经网络模型。

查看onnxruntime获取更多信息。

## Playground Online

[神经风格迁移在线网站](https://kopper.top)

## Deployment

如果您想在自己的电脑上部署该项目，你应该遵循以下步骤。

首先clone该项目：`git clone https://github.com/kopper-xdu/style-transfer.git`

您需要安装flask框架： `pip install flask`

接着您需要做几处修改：

打开 ./templates/index.html 

- 修改102行代码为：`<script src="../static/js/inference_utils/ort.min.js"></script>`
- 删除 95-97行代码

然后您可以直接运行该项目：`python app.py`

### ...... wait to complete






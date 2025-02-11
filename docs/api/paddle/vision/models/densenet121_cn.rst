.. _cn_api_paddle_vision_models_densenet121:

densenet121
-------------------------------

.. py:function:: paddle.vision.models.densenet121(pretrained=False, **kwargs)


121 层的 DenseNet 模型，来自论文 `"Densely Connected Convolutional Networks" <https://arxiv.org/abs/1608.06993>`_ 。

参数
:::::::::

  - **pretrained** (bool，可选) - 是否加载预训练权重。如果为 True，则返回在 ImageNet 上预训练的模型。默认值为 False。
  - **\*\*kwargs** (可选) - 附加的关键字参数，具体可选参数请参见 :ref:`DenseNet <cn_api_paddle_vision_models_DenseNet>`。

返回
:::::::::

:ref:`cn_api_paddle_nn_Layer`，121 层的 DenseNet 模型实例。

代码示例
:::::::::

COPY-FROM: paddle.vision.models.densenet121

## [参数完全一致]torchvision.transforms.functional.to_grayscale

### [torchvision.transforms.functional.to_grayscale](https://pytorch.org/vision/main/generated/torchvision.transforms.functional.to_grayscale.html?highlight=to_grayscale#torchvision.transforms.functional.to_grayscale)

```python
torchvision.transforms.functional.to_grayscale(img: PIL.Image.Image,
                                               num_output_channels: int = 1)
```

### [paddle.vision.transforms.to_grayscale](https://www.paddlepaddle.org.cn/documentation/docs/zh/develop/api/paddle/vision/transforms/to_grayscale_cn.html#to-grayscale)

```python
paddle.vision.transforms.to_grayscale(
    img: Union[PIL.Image.Image, np.ndarray],
    num_output_channels: int = 1
)
```

功能一致，参数完全一致，具体如下：

### 参数映射

| torchvision               | PaddlePaddle       | 备注                      |
|-------------------------- |------------------- |-------------------------- |
| img                       | img                   | 输入图像。              |
| num_output_channels       | num_output_channels   | 输出图像的通道数。       |

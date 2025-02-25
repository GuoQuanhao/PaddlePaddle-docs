# torch.nn.KLDivLoss
### [torch.nn.KLDivLoss](https://pytorch.org/docs/1.13/generated/torch.nn.KLDivLoss.html?highlight=kldivloss#torch.nn.KLDivLoss)

```python
torch.nn.KLDivLoss(size_average=None,
                   reduce=None,
                   reduction='mean',
                   log_target=False)
```

### [paddle.nn.KLDivLoss](https://www.paddlepaddle.org.cn/documentation/docs/zh/api/paddle/nn/KLDivLoss_cn.html#kldivloss)

```python
paddle.nn.KLDivLoss(reduction='mean')
```

两者功能一致但参数不一致，具体如下：
### 参数差异
| PyTorch       | PaddlePaddle | 备注                                                   |
| ------------- | ------------ | ------------------------------------------------------ |
| size_average  | -            | 已弃用。 |
| reduce        | -            | 已弃用。  |
| log_target    | -            | 指定目标是否为日志空间，Paddle 无此功能。  |

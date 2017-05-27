# CountDownButton
封装的倒计时按钮


![](https://github.com/RunerZhang/CountDownButton/blob/master/CountDown.gif)

创建一个倒计时按钮 很简单
```
CountDownButton *btn = [[CountDownButton alloc] initWithFrame:CGRectMake(30, 30, 140, 30) title:@"获取验证码"  btnClick:^{
       ......
    }];
    
[self.view addSubview:btn];

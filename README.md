### 一个简单定时器捕获输入的例子

#### 说明:
PA6口发送1kHz的方波脉冲信号-使用定时器TIM3

PA0口捕获输入-使用定时器TIM2(32位,精度更高). 可连接PA6 


如果是非连续低频信号,可采用普通IO输入中断的方式统计脉冲数.
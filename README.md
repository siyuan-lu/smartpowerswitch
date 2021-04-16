# smartpowerswitch
smartpowerswitch
smartpowerswitch
This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.For more information, please check Tuya Developer Website.
项目是为了向实验用恒温箱提供一个智能电源，其中电源会反馈当前功率大小并且提供定时器的功能。云端收集数据并且通过用户在移动端输入的目标温度数据，功率变化和已工作的时间长度计算当前温度，并且告知用户环境温度是否已处于目标区间。如下图，一个功率曲线图，当前功率和预估当前温度将会被提供给用户，功率曲线图可以放大取值并且数据会贝保存至历史文件中方便查验。移动端会同时显示定时器的剩余时间，用户可以通过按钮马上终止电源或者修改定时器的剩余时间。当用户重新设定目标温度时，一个实时计算的PID曲线将会告知用户何时达到目标温度的稳定区间。![捕获](https://user-images.githubusercontent.com/58858494/114979369-56f77e80-9ebd-11eb-8851-50b4bd5d3d1a.PNG)
![捕获2](https://user-images.githubusercontent.com/58858494/114979371-58c14200-9ebd-11eb-8a83-37144ea303a6.PNG)

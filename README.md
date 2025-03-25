# HillStartModel
.tck file of HillStart

以tck范式描述的双冗余坡道起步辅助系统模型文件

HillStart 为初始模型

HillStartS 为针对安全性属性添加辅助自动机的模型，用于检测安全性属性1-7，在检测时输入 
`tck-reach -a covreach -Li HillStartS.tck `
可以验证对应的安全性属性Si

HillStartLi 为针对活性属性Li进行模型修饰并添加观察自动机的模型，用于检测活性属性1-7，在检测时输入 
`tck-reach -a covreach -Li，LLi HillStartS.tck`
可以验证对应的活性属性Li

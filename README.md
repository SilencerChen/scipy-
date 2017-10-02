# scipy-

windows下安装scipy报错：
  如果直接pip install numpy后再pip scipy大概率会报错
  解决方法就是将numpy和scipy都是用whl的方法安装
  
可能的原因：
  scipy需要对numpy和mkl的依赖
  whl直接提供numpy+mkl
  直接pip install numpy可能不包含mkl的安装

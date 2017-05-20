# JDATA算法大赛入门(LB 0.08553(F11:0.10404/F12:0.07320)+时间滑动窗口特征＋xgboost模型)
在0.07baseline的基础上改进的
减少了cache文件的空间占用

## 依赖库

- pandas
- sklearn
- xgboost

## 项目结构

- data: 储存数据目录
- cache: 缓存目录
- sub: 结果目录
- train: 训练代码
- gen_feat: 生成特征

## 使用说明

python train.py

## 使用注意
第一次运行时会产生大量的中间文件，大约需要4G硬盘空间，同时也会占用大量的内存，大约20G，如果出现了MemoryError，可以尝试结束进程并重新运行，读取中间文件可以节约时间。

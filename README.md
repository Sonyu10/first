#### 3D generation：

1.triposr; 2.rodin gen

主要存在问题：
1.单视图背面部分生成效果差
2.细节部分生成模型与图片存在差异
3.多次redo生成的模型差异较大，存在一定的不稳定性

#### 3d highlighter

主要问题：
1.泛化能力较差
2.高亮步骤较为依赖文本描述的准确性
3.文件生成的高亮区域部分质量不稳定

工作内容：
1.如何优化高亮区域部分的质量
2.减少模型对于文本描述的依赖性


#### 后期工作：

1.确定生成模型
2.语义分割创新点
3.搜集图片开始制作数据集


## Installation

Install and activate the conda environment with the following commands. 
```
conda env create --file 3DHighlighter.yml
conda activate 3DHighlighter
```
Note: The installation will fail if run on something other than a CUDA GPU machine.



#### System Requirements
- Python 3.9
- CUDA 11
- 16 GB GPU

## Run Examples

Run the scripts below to get example localizations.
```
# hat on a candle
./demo/run_candle_hat.sh
# hat on a dog
./demo/run_dog_hat.sh
# shoes on a horse
./demo/run_horse_shoes.sh
```


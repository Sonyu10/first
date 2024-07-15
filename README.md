#### 3D generation：
1.triposr; 2.rodin gen

生成中主要存在问题：
1.单视图背面部分生成效果差
2.细节部分生成模型与图片存在差异
3.多次redo生成的模型差异较大，存在一定的不稳定性


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


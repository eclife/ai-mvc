<code>conda install -c apple tensorflow-deps 
pip install tensorflow-macos tensorflow-metal
pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cpu</code>

<code>conda create -n ai-mvc python=3.10
conda activate ai-mvc</code>
<code>conda install -c apple tensorflow-deps  # 安装依赖
pip install tensorflow-macos tensorflow-metal  # 启用 GPU 加速</code>

<code>pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cpu</code>

<code>pip install jupyterlab matplotlib scikit-learn pandas  # Jupyter 和数据处理</code>

激活mvc
<code>conda activate ai-mvc</code>

<code>python
import tensorflow as tf
print(tf.config.list_physical_devices('GPU'))  # 应显示 Metal 设备</code>

<code>python
import torch
print(torch.backends.mps.is_available())  # 应输出 True</code>

# lightweight_3DSSG
Lightweight 3D Semantic Scene Graph Prediction Model


# CUDA 12.2 Version
conda create -n vlsat python=3.8
conda activate vlsat
pip install -r requirement.txt
pip install torch==2.2.1 torchvision==0.17.1 torchaudio==2.2.1 --index-url https://download.pytorch.org/whl/cu121
pip install torch-scatter torch-sparse torch-spline-conv -f https://data.pyg.org/whl/torch-2.2.0+cu121.html
pip install torch_geometric
pip install git+https://github.com/openai/CLIP.git

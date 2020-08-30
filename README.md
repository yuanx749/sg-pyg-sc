# sg-pyg-sc
Install [conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)

Install [StellarGraph](https://stellargraph.readthedocs.io/en/stable/index.html), [Scanpy](https://scanpy.readthedocs.io/en/stable/), [PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/)

```bash
conda install -c conda-forge notebook
conda install -c stellargraph stellargraph
pip install pydot pydotplus graphviz

pip install scanpy[louvain,leiden]
pip install pynndescent
pip install phate

conda install -c conda-forge ipywidgets
conda install pytorch torchvision cpuonly -c pytorch
pip install torch-scatter==latest+cpu -f https://pytorch-geometric.com/whl/torch-1.6.0.html
pip install torch-sparse==latest+cpu -f https://pytorch-geometric.com/whl/torch-1.6.0.html
pip install torch-cluster==latest+cpu -f https://pytorch-geometric.com/whl/torch-1.6.0.html
pip install torch-spline-conv==latest+cpu -f https://pytorch-geometric.com/whl/torch-1.6.0.html
pip install torch-geometric
```
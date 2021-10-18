# Point-Cloud-Part-Segmentation

# DGCNN
A PyTorch implementation of DGCNN based on AAAI 2018 paper 
[An End-to-End Deep Learning Architecture for Graph Classification](https://www.cse.wustl.edu/~muhan/papers/AAAI_2018_DGCNN.pdf).

## Requirements
- [Anaconda](https://www.anaconda.com/download/)
- [PyTorch](https://pytorch.org)
- [PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/)
```
conda install pyg -c pyg -c conda-forge
```



# Dataset
1) ShapeNet
ShapeNet is a large collection of 3D objects e.g. bicycles,
planes, bottles, chairs, tables, etc. that are developed by a team
of researchers from Stanford and Princeton universities as
well as TTIC institute. Two categories datasets are available
that is ShapeNet Core that includes 51,300 3D models that
are divided into 55 classes and ShapeNetSem which consist
of 270 classes of 12,000 models.

2) ModelNet
The ModelNet dataset is a comprehensive collection of clean
3D CAD models provided by researchers from department
of computer Science of Princeton University. The datasets
contain 127,915 CAD models belonging to 662 object categories. It is obtained using online search engines after querying for each object category and then manually annotated
the data. ModelNet has two subsets which ModelNet10 and
ModelNet40 that are mostly used in object recognition and
classification tasks.

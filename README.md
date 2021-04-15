# rds_conversion


#### environment

Create environment from conda environment .yaml file
```bash
conda env create -f env.yaml
```


#### running

Only stable notebook right now is basic_rds_to_h5ad_conversion.ipynb. Shows how to convert seurat RDS object into scanpy .h5ad object while transfering counts and sctransform normalized expression.

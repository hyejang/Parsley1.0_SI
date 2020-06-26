# Parsley1.0_SI

This repository contains scripts, whose details are available in our preprint. 

## Data stored in Github repo:  
```
|-- 1_valence_parameter_fitting/
|   |-- README.md
|   |-- 1_dataset_generation/
|   |   |-- roche_set/
|   |   |   |-- 2019-05-16-Roche-Optimization_Set/ 
|   |   |   |-- 2019-07-09-OpenFF-Optimization-Set/ 
|   |   |   |-- 2019-05-01-OpenFF-Group1-Torsions/ 
|   |   |-- coverage_set/
|   |   |   |-- 2019-06-25-smirnoff99Frost-coverage/
|   |   |   |-- 2019-07-01-smirnoff99Frost-coverage-torsion/ 
|   |-- 2_forcebalance_optimization/
|   |   |-- 1_fb_target_gen/
|   |   |   |-- make_fb_optgeo_target.py 
|   |   |   |-- make_vib_freq_target.py 
|   |   |   |-- make_torsion_target_new.py 
|   |   |-- 2_input_components/ 
|   |   |   |-- optimize.in
|   |   |   |-- forcefield/
|-- 2_benchmarking/
|   |-- test_dataset_generation/ 
|   |   |-- divide_sets.ipynb
|-- 3_physical_property_datasets/
|   |-- physical_properties/
```
#### Descriptions 

-  `1_valence_parameter_fitting/README.md`: OpenFF ForceBalance fitting tutorial[(original location)](https://github.com/openforcefield/openforcefield-forcebalance/blob/master/README.md)

- `2019-05-16-Roche-Optimization_Set/`: Roche optimization dataset construction and submission [(original location)](https://github.com/openforcefield/qca-dataset-submission/tree/master/2019-05-16-Roche-Optimization_Set)

- `2019-07-09-OpenFF-Optimization-Set/`: Roche hessian dataset construction and submission [(original location)](https://github.com/openforcefield/qca-dataset-submission/tree/master/2019-07-09-OpenFF-Optimization-Set)

- `2019-05-01-OpenFF-Group1-Torsions/`: Roche torsiondrive dataset construction and submission [(original location)](https://github.com/openforcefield/qca-dataset-submission/tree/master/2019-05-01-OpenFF-Group1-Torsions)

- `019-06-25-smirnoff99Frost-coverage/`: coverage optimization and hessian dataset construction and submission [(original location)](https://github.com/openforcefield/qca-dataset-submission/tree/master/2019-06-25-smirnoff99Frost-coverage)

- `2019-07-01-smirnoff99Frost-coverage-torsion/`: coverage torsiondrive dataset construction and submission [(original location)](https://github.com/openforcefield/qca-dataset-submission/tree/master/2019-07-01-smirnoff99Frost-coverage-torsion)


- `make_fb_optgeo_target.py`: a python script for ForceBalance readable optgeo target generation [(original location)](https://github.com/openforcefield/openforcefield-forcebalance/raw/master/optimized_geo/make_fb_optgeo_target.py)

- `make_vib_freq_target.py`: a python script for ForceBalance readable vibfreq target generation [(original location)](https://github.com/openforcefield/openforcefield-forcebalance/blob/master/vib_freq_target/make_vib_freq_target.py)

- `make_torsion_target_new.py`: a python script for ForceBalance readable torsiondrive target generation [(original location)](https://github.com/openforcefield/openforcefield-forcebalance/blob/master/torsion_target/make_torsion_target_new.py)

- `optimize.in`: input file for ForceBalance optimization [(original location)](https://github.com/openforcefield/openforcefield-forcebalance/releases/tag/v1.0.0-RC2)

- `forcefield/`: input forcefield directory for ForceBalance optimizaiton [(original location)](https://github.com/openforcefield/openforcefield-forcebalance/releases/tag/v1.0.0-RC2)

- `divide_sets.ipynb`: script for dividing a large benchmark set into these two sets using path-based fingerprint method [(original location)](https://github.com/openforcefield/release-1-benchmarking/blob/master/QM_molecule_selection/divide_sets.ipynb)

- `physical_properties/` : contains scripts for automated curation of physical property datasets and benchmarking results against condensed phase liquid properties [(original location)](https://github.com/openforcefield/release-1-benchmarking/tree/master/physical_properties)


## Data stored in zenodo: 
```
|-- forcefield_releases/
|   |-- parsley/
|   |   |-- v0.0.9/
|   |   |-- v1.0.0-RC1/ 
|   |   |-- v1.0.0-RC2/ 
|   |-- smirnoff99Frosst/
|   |   |-- smirnoff99Frosst-1.1.0/
|-- qm_datasets/
|   |-- training_datasets/
|   |   |-- 01_Roche_set/ 
|   |   |   |-- roche_optimization_set_gen.tar.gz
|   |   |   |-- roche_hessian_set_gen.tar.gz  
|   |   |   |-- roche_torsiondrive_set_gen.tar.gz
|   |   |-- 02_Coverage_set/
|   |   |   |-- Utility-All-Parameters.tar.gz 
|   |   |   |-- coverage_optimization_set_gen.tar.gz 
|   |   |   |-- coverage_torsiondrive_set_gen.tar.gz 
|   |-- test_datasets/ 
|   |   |-- discrepancy_optimization_set_gen.tar.gz
|   |   |-- pfizer_optimization_set_gen.tar.gz
|   |   |-- fda_drugs_optimization_set_gen.tar.gz
|-- physical_property_datasets/
|   |-- test_datasets/ 
|   |   |-- physical_properties_benchmark.tar.gz 
|-- utils/
|   |-- fragmenter-87b85a4.zip
|   |-- openforcefield-0.4.1/
```
#### Descriptions 

- `v0.0.9`: 

- `v1.0.0-RC1/`: contains assets from `Parsley v1.0.0-RC1` release notes [(original location)](https://github.com/openforcefield/openforcefield-forcebalance/releases/tag/v1.0.0-RC1)

- `v1.0.0-RC2/`: contains assets from `Parsley v1.0.0-RC2` release notes [(original location)](https://github.com/openforcefield/openforcefield-forcebalance/releases/tag/v1.0.0-RC2)

- `smirnoff99Frosst-1.1.0/`: contains assets from `smirnoff99Frosst v1.1.0` release notes(https://github.com/openforcefield/smirnoff99Frosst/releases/tag/1.1.0)

- `roche_optimization_set_gen.tar.gz`: optimization data set construction [(original location)](https://github.com/openforcefield/qca-dataset-submission/tree/2019-05-16-Roche-Optimization_Set)

- `roche_hessian_set_gen.tar.gz`: vibrational data set construction [(original location)](https://github.com/openforcefield/qca-dataset-submission/tree/master/2019-07-09-OpenFF-Optimization-Set)

- `roche_torsiondrive_set_gen.tar.gz`: torsiondrive data set construction [(original location)](https://github.com/openforcefield/qca-dataset-submission/tree/master/2019-05-01-OpenFF-Group1-Torsions)

- `Utility-All-Parameters.tar.gz`: Construction of the original coverage set [(original location)](https://github.com/openforcefield/open-forcefield-data/tree/master/Utilize-All-Parameters)

- `coverage_optimization_set_gen.tar.gz`: optimization, hessian data set construction [(original location)](https://github.com/openforcefield/qca-dataset-submission/tree/master/2019-06-25-smirnoff99Frost-coverage) 

- `coverage_torsiondrive_set_gen.tar.gz`: torsiondrive data set construction [(original location)](https://github.com/openforcefield/qca-dataset-submission/tree/master/2019-07-01-smirnoff99Frost-coverage-torsion)

- `discrepancy_optimization_set_gen.tar.gz`: [(original location)](https://github.com/openforcefield/qca-dataset-submission/blob/master/2019-07-05%20eMolecules%20force%20field%20discrepancies%201)

- `pfizer_optimization_set_gen.tar.gz`:  [(original location)](https://github.com/openforcefield/qca-dataset-submission/tree/master/2019-09-07-Pfizer-discrepancy-optimization-dataset-1)

- `fda_drugs_optimization_set_gen.tar.gz`:  [(original location)](https://github.com/openforcefield/qca-dataset-submission/tree/master/2019-09-08-fda-optimization-dataset-1)

- `physical_properties_benchmark.tar.gz` : contains scripts for automated curation of physical property datasets and benchmarking results against condensed phase liquid properties [(original location)](https://github.com/openforcefield/release-1-benchmarking/tree/master/physical_properties)

- `fragmenter-87b85a4.zip`: fragmenter v0.0.2+121.g87b85a4 used for the datasets used for Parsley 1.0 [(original location)](https://github.com/openforcefield/fragmenter/tree/87b85a406aa9c6ac0cfbaf582ed05c55799161a9)

- `openforcefield-0.4.1/`: openforcefield toolkits v0.4.1 [(original location)](https://github.com/openforcefield/openforcefield/releases/tag/0.4.1)
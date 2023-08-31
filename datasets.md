| Dataset  | Task  | #Samples | #Tasks | Domain         | Split       | Metric       | Date  | Benchmark      | Source  |
| :---     | ---:  | ---:     | ---:   | ---:           | ---:        | ---:         | ---:  | ---:           | ---:    |
| QM7      | PP    | 7,165    | 1      | Molecule       | Stratified  | MAE          | 2012* | MoleculeNet    | [GDB-13],[MoleculeNet](https://moleculenet.org/) |
| QM7-b    | PP    | 7k       | 14     | Molecule       | Random      | MAE          | 2014  | MoleculeNet    | [GDB-13],[info](http://quantum-machine.org/datasets/) [info](https://deepchem.readthedocs.io/_/downloads/en/2.4.0/pdf/)|
| QM8      | PP    | 22k      | 12     | Molecule       | Random      | MAE          | 2014  | MoleculeNet    | [GDB-17],[info](http://quantum-machine.org/datasets/) |
| QM9      | PP,GM | 130-134k | 12-19  | Molecule       | Random      | MAE          | 2012  | MoleculeNet    | [GDB-17],[info](http://quantum-machine.org/datasets/),[PyG](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.datasets.QM9.html) |
| PDBbind  | PP    | 5k-13k   | 1      | Protein-ligand | Time        | RMSE         | 2004* | MoleculeNet    | [PDB](https://www.rcsb.org/search),[info](https://deepchem.readthedocs.io/_/downloads/en/2.4.0/pdf/) |
| ANI-1    | PP    | 22M      | 1      | Molecules      | -           | MAE, ROC AUC | 2017  | -         | [GDB-11][github](https://github.com/isayev/ANI1_dataset) [data-git](https://github.com/atomistic-machine-learning/schnetpack/blob/dce002f1befe9bd1ccd5efb7651a1f6ed7c224a8/src/schnetpack/datasets/ani1.py)  |
| Alchemy  | PP    | 120k     | 12     | Molecule       | Stratified* | MAE          | 2019  | [Alchemy Contest](https://alchemy.tencent.com/#leaderboard) | [GDB MedChem](https://gdb.unibe.ch/downloads/), [link](https://alchemy.tencent.com/), [link]{https://huggingface.co/graphs-datasets}{HF}] |
| Matbench  | PP    | 1k-100k  | 13     | Molecules      | StratifiedKFold*| MAE, ROC-AUC | 2019 | Mathbench| [Materails Project](https://next-gen.materialsproject.org/)[data](https://ml.materialsproject.org/) | |
| Atom3D     | PP      | Varied      | 8       | Mol., RNA, Prot. | Varied       | Various    | 2021 | [Varied](https://github.com/drorlab/atom3d)             | % collection = yes
| Jarvis     | PP      | 1k-800k     | Many   | Random*        | Molecules      | MAE          | 2020* | | [Nist-Jarvis](https://pages.nist.gov/jarvis/databases/)  | [xxx](https://arxiv.org/abs/...) |  % collection = yes
OC20         | PP,MD  | 560k-133M    | 3        | Materials     | Extrapolation*   | MAE, EwT  | 2020*  | [OCP](https://opencatalystproject.org/)  | [Materials Project](https://next-gen.materialsproject.org/)           |
| OC22       | PP,MD  | 50k-10M      | 3       | Materials      | Extrapolation*    | MAE, EwT     | 2022* | OCP| [Materials Project](https://materialsproject.org/)           |
| QM7-X      | PP,MD  | 4.2M        | 42       | Molecule       | Extrapolation | MAE  | 2022 | - | [GDB-13](https://gdb.unibe.ch/downloads/) |
| MD17       | MD     | 150k-1M         | 10        | Molecule                 | ?               | MAE                  | 2017* | [info](http://quantum-machine.org/datasets/)[PyG](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.datasets.MD17.html#torch_geometric.datasets.MD17)[HF](https://huggingface.co/graphs-datasets)[git](https://github.com/atomistic-machine-learning/schnetpack/blob/dce002f1befe9bd1ccd5efb7651a1f6ed7c224a8/src/schnetpack/datasets/md17.py#L188)             |
| ISO17      | MD    | 645K          | 1       | Molecule                 | Extrapolation          | MAE                | 2016 | - | [QM9](http://www.quantum-machine.org/datasets/#md-datasets)             | -
| MDAnalysis | MD    | 
| 3BPA       | MD    | 2,139         | 1      | Molecule                  | -                  | RMSE                   | 2020 | - | [xxx](...)             |
| GEOM       | GM    | 37M           | 1      | Molecule                  | Random             | MAE, RMSD              | 2021* | GEOM | [github](https://github.com/learningmatter-mit/geom) |
| ProteinNet   | SP   | -              | -        | -                   | -               | -                    |  | -             | - |
| Molecule3D   | SP   | 3.9M           | 4        | Molecules               | Random             | MAE, RMSE, validity  | 2021 | - | [PubChemQC](https://arxiv.org/pdf/2110.01717.pdf) |    % Scaffold        |
| CASP         | SP   | 45K            | 1        | Proteins                | ?*   | ?        | 2013* | - | [link](https://arxiv.org/pdf/2110.01717.pdf)             |
| ModelNet     | CV  | -          | -        | -                   | -               | -                    |  | -             | |
| ShapeNet     | CV   | -          | -        | -                   | -               | -                    |  | -             | |
| ScanNet      | CV  | -          | -        | -                   | -               | -                    |  | -             |  |

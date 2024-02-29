# Geometric-GNNs

In this readme, you will find a list of Geometric GNNs for 3D atomic systems, (hopefully) maintained up-to-date by the community. 
For each method, we include its associated Geometric GNN family, tensor type and body order information. Check out the accompanying paper for more details: [A Hitchhiker's Guide to Geometric GNNs for 3D atomic systems ](https://arxiv.org/abs/2312.07511).

In the rest of the repository, you will find a [list of datasets for Geometric GNNs](https://github.com/zetayue/geometric-gnns/blob/main/datasets.md) as well as a [list of useful software libraries](https://github.com/AlexDuvalinho/geometric-gnns/blob/main/software.md). 


<figure><center><img src="image/timeline.png" width="100%"></center></figure>


| Method | Year | Family | Tensor type | Body order | Source |
| :---  | ---: | ---:   | ---:         | ---: | ---: |
|SchNet| 2017| invariant	| scalar	| 2 | [paper](https://arxiv.org/pdf/1706.08566.pdf) |
|CGCNN|	2017|	invariant|	scalar|	2| [paper](https://arxiv.org/abs/1710.10324)|
|TFN|	2018|	equivariant|	spherical|	2|  [paper](https://arxiv.org/pdf/1802.08219.pdf)|
|PhysNet|	2019|	invariant|	scalar|	2| [paper](https://arxiv.org/pdf/1902.08408.pdf) |
|DimeNet|	2019|	invariant|	scalar|	3| [paper](https://arxiv.org/pdf/2003.03123.pdf)|
|MEGnet|	2019|	invariant||		| [paper](https://arxiv.org/abs/1812.05055)|
|Cormorant|	2019|	equivariant|	spherical|	2| [paper](https://arxiv.org/pdf/1906.04015.pdf)|
|MXMNet|	2020|	invariant|	scalar|	3| [paper](https://arxiv.org/pdf/2011.07457.pdf)|
|DimeNet++|	2020|	invariant|	scalar|	3| [paper](https://arxiv.org/abs/2011.14115)|
|GVP-GNN|	2020|	equivariant|	cartesian|	3| [paper](https://arxiv.org/pdf/2009.01411.pdf)|
|LieTransformer| 2020| equivariant |  | | [paper](https://arxiv.org/abs/2012.10885)|
|LieConv| 2020 | equivariant |	|| [paper](https://arxiv.org/abs/2002.12880)|
|SE3-Transformers|	2020|	equivariant| spherical|		| [paper](https://arxiv.org/abs/2006.10503)|
|SpinConv|	2021|	invariant| spherical|| [paper](https://arxiv.org/abs/2106.09575)|
|ForceNet|	2021|	unconstrained| scalar|	2| [paper](https://arxiv.org/abs/2103.01436)|
|Graphormer|	2021|	invariant| scalar |	| [paper](https://arxiv.org/abs/2106.05234)|
|SphereNet|	2021|	invariant|	scalar|	4| [paper](https://arxiv.org/abs/2102.05013)|
|GemNet|	2021|	invariant|	scalar|	4| [paper](https://arxiv.org/abs/2106.08903)|
|ChIRo|	2021|	invariant|	scalar|	| [paper](https://arxiv.org/abs/2110.04383)|
|SEGNN|	2021|	equivariant|	spherical|	2| [paper](https://arxiv.org/abs/2110.02905)|
|EGNN|	2021|	equivariant|	cartesian|	2| [paper](https://arxiv.org/pdf/2102.09844.pdf)|
|PaiNN|	2021|	equivariant|	cartesian|	3| [paper](https://arxiv.org/abs/2102.03150)|
|NeuquIP|	2021|	equivariant|	spherical|	2| [paper](https://arxiv.org/abs/2101.03164)|
|SpookyNet|	2021|	invariant| scalar |	 2| [paper](https://arxiv.org/abs/2105.00304)|
|EQGAT|	2022|	equivariant|	cartesian|	2| [paper](https://arxiv.org/pdf/2202.09891.pdf)|
|Torch-MDNet|	2022|	equivariant|	cartesian|	2| [paper](https://arxiv.org/abs/2202.02541)|
|GNS|	2022|	unconstrained |	scalar|	| [paper](https://arxiv.org/abs/2002.09405)|
|GNN-LF|	2022|	invariant|	scalar|| [paper](https://arxiv.org/abs/2208.00716)|
|GCPNet|	2022|	equivariant| cartesian| |[paper](https://arxiv.org/abs/2211.02504) |
|ComENet|	2022|	invariant|	scalar|4| [paper](https://arxiv.org/pdf/2206.08515.pdf)|
|So3krates|	2022|	equivariant|	cartesian|	2| [paper](https://arxiv.org/abs/2205.14276)|
|Equiformer|	2022|	equivariant|	spherical|	2| [paper](https://arxiv.org/abs/2206.11990)|
|MACE|	2022|	equivariant|	spherical |Many| [paper](https://arxiv.org/abs/2206.07697)|
|GemNet-OC|	2022|	invariant|	scalar|	4| [paper](https://arxiv.org/abs/2204.02782)|
|ClofNet|	2022|	equivariant|	cartesian|	| [paper](https://arxiv.org/pdf/2110.14811.pdf)|
|Allegro| 2022| equivariant |  spherical | Many| [paper](https://arxiv.org/abs/2204.05249)|
|LEFTNet|	2023 | equivariant|	cartesian || [paper](https://arxiv.org/abs/2304.04757)|
|ViSNet-LSRM|	2023|	equivariant |	cartesian|	| [paper](https://arxiv.org/pdf/2304.13542.pdf)|
|SCN|	2023|	unconstrained|	spherical	| | [paper](https://arxiv.org/abs/2206.14331)|
|TensorNet|	2023| equivariant |	cartesian || [paper](https://arxiv.org/abs/2306.06482)|
|eSCN|	2023|	equivariant|	spherical|	2| [paper](https://arxiv.org/abs/2302.03655)|
|FAENet|	2023|	unconstrained | scalar |	Many| [paper](https://arxiv.org/abs/2305.05577)|

<figure><center><img src="image/axes.png" width="75%"></center></figure>


## Contact

Authors: Alexandre Duval (alexandre.duval@mila.quebec), Simon V. Mathis (simon.mathis@cl.cam.ac.uk), Chaitanya K. Joshi (chaitanya.joshi@cl.cam.ac.uk), Victor Schmidt (schmidtv@mila.quebec). 

We welcome your questions and feedback via email or GitHub Issues.

## Citation

```
@article{duval2023hitchhikers,
  title   = {A Hitchhiker's Guide to Geometric GNNs for 3D Atomic Systems},
  author  = {Alexandre Duval and Simon V. Mathis and Chaitanya K. Joshi and Victor Schmidt and Santiago Miret and Fragkiskos D. Malliaros and Taco Cohen and Pietro Lio and Yoshua Bengio and Michael Bronstein},
  year    = {2023},
  journal = {arXiv preprint arXiv: 2312.07511}
}
```

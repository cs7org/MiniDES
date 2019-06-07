# MiniDES

<img src="https://github.com/cs7org/MiniDES/blob/master/wiki_images/commtree.png" alt="commtree" width="20%"/>

The lightweight Discrete-Energy-Simulator (DES) is a basic framework to model distributed energy resources, allowing synchronized time progress on arbitrary resource sets and incorporating queries to ease control and post-processing. 
Communities are built bottom up as a collection of resource sets/subsets to enable modular and customizable simulation setups. The entire framework resides within a jupyter notebook.

- object-oriented python3 + numpy for fast in-mem postprocessing
- customizable resource models of flexible spatiotemporal resolution
- start modeling by extending the template examples (case study is more extensive)
- all open-source (MIT)

The structure of the framework is outlined in the [Wiki](https://github.com/cs7org/MiniDES/wiki). The Wiki describes the workflow and explains the existing models/resources, accompanied by multiple examples. Simulations regarding electrical power flow rather than energy balances (used in this tool), are conducted via file import/export to [OpenDSS](https://sourceforge.net/projects/electricdss/).

# Install

There are no installation requirements beside a functional [jupyter notebook](https://jupyter.readthedocs.io/en/latest/install.html) based on python 3. The template is also available in `template.hmtl` to preview simulated examples.

The following paper accommodates the work:
```
MiniDES - Lightweight Simulation Framework for interconnected renweable resources
```
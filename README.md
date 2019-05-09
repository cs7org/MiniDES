# MiniDES

<img src="https://github.com/cs7org/MiniDES/blob/master/wiki_images/commtree.png" alt="commtree" width="20%"/>

The lightweight Distribution-Energy-Simulator (DES) is a basic framework to model distributed energy resources, allowing synchronized time progress on arbitrary resource sets and incorporating queries to ease control and post-processing. 
Communities are built bottom up as a collection of resource sets/subsets to enable modular and customizable simulation setups. The entire framework resides within a jupyter notebook, offering a template to start modeling right away. It is open source available.

Preferences of this tool:
1. Lightweight, open-source in object-oriented python + numpy
   - portable code base and no installation (except JPN)
   - browser GUI, wrapping the kernel to selectively do runs and plots
   - open source MIT license
2. Fully customizable resource models
   - base class to build custom resources/controls (low-level + queries)
   - predefined key figures e.g. SSR,SCR in time-series or total
   - aggregator model to build/query collections of any height
   - time model allows for variable simulation length/resolution
3. Object-oriented despite separation of function and data.
   - direct post-processing of in memory data
   - data model allows for direct slicing/indexing/aggregating

The structure of the framework is outlined in the [Wiki](https://github.com/cs7org/MiniDES/wiki). The Wiki describes the workflow and explains the existing models/resources, accompanied by multiple examples. Simulations regarding electrical power flow rather than energy balances (used in this tool), are conducted via file import/export to [OpenDSS](https://sourceforge.net/projects/electricdss/).

# Install

There are no installation requirements beside a functional [jupyter notebook](https://jupyter.readthedocs.io/en/latest/install.html) based on python 3. The template is also available in `template.hmtl` to preview simulated examples.

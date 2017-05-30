# Software installation

Steps required to install software required for tutorial



### 1. KNIME and 3D-e-Chem KNIME nodes

Install KNIME 3.3.1 + all free extensions from [https://www.knime.org/downloads/overview](https://www.knime.org/downloads/overview)

In KNIME go to Help &gt; Install New Software…

Add the following update site: [https://3d-e-chem.github.io/knime-node-collection](https://3d-e-chem.github.io/knime-node-collection)

Click the checkbox and install the 3D-e-Chem KNIME node collection, then restart KNIME

The GPCRdb, KLIFS, Molviewer and ss-TEA nodes are ready to be used.



### 2. SyGMA and KRIPOdb

To be able to use the SyGMa and KripoDB nodes, do the following:

Install Miniconda for Python 2.7 from [https://conda.io/miniconda.html](https://conda.io/miniconda.html)

Open the Anaconda Prompt and execute the following commands:

`conda install -c 3d-e-Chem -c rdkit -c conda-forge pandas protobuf rdkit git scipy sygma`

`pip install git+https://github.com/3D-e-Chem/kripodb.git`

In KNIME go to File &gt; Preferences &gt; KNIME &gt; Python and select your new Python executable \(e.g. C:\ProgramData\Miniconda2\python.exe\)



### 3. PLANTS KNIME nodes

To be able to use the PLANTS nodes, do the following:

In KNIME go to Help &gt; Install New Software…

Add the following update site: [https://3d-e-chem.github.io/updates ](https://3d-e-chem.github.io/updates )

Check the KNIME PLANTS checkbox and install, then restart KNIME

The PLANTS executable can be downloaded from [http://www.mnf.uni-tuebingen.de/fachbereiche/pharmazie-und-biochemie/pharmazie/pharmazeutische-chemie/pd-dr-t-exner/research/plants.html](http://www.mnf.uni-tuebingen.de/fachbereiche/pharmazie-und-biochemie/pharmazie/pharmazeutische-chemie/pd-dr-t-exner/research/plants.html)




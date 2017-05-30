# Creating the first workflow to access GPCR data

## Importing workflows

* Download the workshop material which consists of several KNIME workflow \(.knwf\) files

* At each exercise import the specified workflow by going to the menu bar, clicking on **File **and** Import KNIME Workflow…  **
* Browse to the file** workflow\_name.knwf  **
* Click **Finish **then double click on the imported workflow in the left panel to open it
* You will also create a workflow yourself, but you can always refer to the provided workflows to see how the nodes work and to check the configuration settings

## Creating your first workflow

* In the menu bar click on **File **and** New…  **
* Click **Next**, then give the workflow a name, finally click **Finish  **
* Find the **GPCRDB Protein families **node in the** Node repository **and drop it to the workspace
* Right click on the node and click **Configure…** – you can see that the only setting this node takes is the URL of GPCRdb, therefore you don’t need to change anything now
* Right click on the node and click **Execute**, wait until the status becomes green
* Right click on the node and open the Out-Port table – you can see a hierarchical list of GPCRs with their identifiers and names in the table

![](/assets/gpcrdb-protein-families.png)

> **Q**: The **Slug** is a hierarchical identifier of GPCRs. The first three digits determine the class, the second three digits the ligand type, the third three digits the subfamily and the fourth three digits the subtype, e.g. 001\_001\_002\_001 means class A, aminergic, acetylcholine receptors, M1




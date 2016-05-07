# Usage of Plotly Bar Chart in SPSS Modeler
##### Description:

This extention allows you to create good looking offline (no need pass data or library queries through internet) interactive D3.js bar chart, which is generated by Plotly R library. Generated graph are fully interactive and can be shown in any web browser. The main advantage of these graph is that you can plot additinal information, which can not be done with a standard SPSS graphs nodes. In addition you can zoom charts and slide them. 
---

##### This extension adds a new node:

<img src="https://raw.githubusercontent.com/OndrejSzekely/Bar_Charts_with_Plotly/master/screenshots/bar1.PNG" width="73">

Option tab of these node is described in documment protocol_en.pdf stored in docs folder. [Documentation][2]

##### Screenshots of outputs: 
![Output1](https://raw.githubusercontent.com/OndrejSzekely/Bar_Charts_with_Plotly/master/screenshots/bar3.PNG)

##### Screenshots of Options tabs: 
<img src="https://raw.githubusercontent.com/OndrejSzekely/Bar_Charts_with_Plotly/master/screenshots/bar4.PNG" width="520">
---
---
Requirements
----
- IBM SPSS Modeler v17.1 or higher.
- R Essentials for SPSS Modeler plugin
- R 3.1.2 or higher

---
Installation instructions
----
1. Download the extension: [Download][5]
2. Close SPSS Modeler. Save the .cfe files in the CDB folder of the IBM SPSS Modeler. The default location of the CDB folder on Windows 7 is ”C:\ProgramData\IBM\SPSS\Modeler\17\CDB”. If the ProgramData folder is hidden type the path manually. All needed R packages are downloaded and installed automatically when SPSS stream is launched.
3. Restart IBM SPSS Modeler, the node will now appear in the Output palette.

---
R Packages used
----
The R packages will be installed the first time the node is used as long as an Internet connection is available.

- [plotly][7]
- [Psych][8]


---
Documentation and samples
----
- Find a PDF with the documentation of this extension in the [Documentation][2] directory
- There is a sample available in the [Example][3] directory


---
License
----

[MIT][1]


Contributors
----

  - Ondrej Szekely ([email](oszekely@cz.ibm.com))

##### Updates:
- Problems with overlay option are fixed (Histogram, Bar Chart).

[1]: https://opensource.org/licenses/MIT
[2]: https://github.com/OndrejSzekely/Modeler_Plotly/tree/master/docs
[3]: https://github.com/OndrejSzekely/Modeler_Plotly/tree/master/example
[5]: https://github.com/OndrejSzekely/Modeler_Plotly/tree/master/src
[7]: https://plot.ly
[8]: https://cran.r-project.org/web/packages/psych/index.html

# CMAE Folder Structure Updates:

***
[CMAE Chiller EDR](https://windchill.apps.carrier.com/Windchill/app/#ptc1/tcomp/infoPage?oid=OR%3Awt.folder.Cabinet%3A4766459&u8=1&ContainerOid=OR:wt.projmgmt.admin.Project2:4766407&redirect=false)
![CMAE EDR](../../picture/TubeEDR/structure4.jpg)

[//]: 换行

**1. Sections Combination Happened `both in "Master" and "Current" folder`:**
> Tube EDR folder Structure in Windchill **BEFORE** was:
> * 17-19-23 C section：
Records tube weight information；
> * 17-19-23 D section: 
Records tube dimensions;
> * 17-19-23 G section: 
Records both heat transfer / water >pressure methodologies and necessary data.
![onlyGsection](../../picture/TubeEDR/structure2.jpg)

> Tube EDR folder Structure in Windchill **NOW** is:
> * 17-19-23 G section: 
Combine 17-19-23 C and D and G together, into G sction. Records tube weight, dimension, heat transfer and water pressure methodologies, necessary heat transfer and water pressure drop data.

**2. Two Seperated G Section Files`both in "Master" and "Current" folder`:**
> **BEFORE**: Only one 17-19-23 G file, all heat transfer content is implemented in this word/pdf section file.

> **NOW**:
> Two seperated section files are used.
> * 17-19-23 G with methodology: word / pdf file;
> * 17-19-23 G with data: excel file.
![onlyGsection](../../picture/TubeEDR/structure1.jpg)
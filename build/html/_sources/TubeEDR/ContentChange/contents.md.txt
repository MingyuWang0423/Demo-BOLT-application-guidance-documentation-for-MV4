# EDR Updated Contents Summary:
***
**1. Change in 17-19-23 tube EDR word / pdf file:**
>* All data tables are removed, replaced with a new data location comment.
>![pdf content](../../picture/TubeEDR/content-pdf.jpg)

**2. Change in 17-19-23 tube EDR excel file:**
In 17-19-23 G data part:

* `Change records:`
>![records](../../picture/TubeEDR/content-record.jpg)
>* Includes:
>   * Date: The date a change in EDR happened;
>   * Sheet: in which tube data is changed;
>   * Tube Desination: Tube names;
>   * Comments: Give comments on the changes to help understand.
>   * Prepared by: EDR owner;
>   * Reviewed by: 1st level approval;
>   * Approved by: 2nd level approval.

* `Geometry:`
>![records](../../picture/TubeEDR/content-Geometry.jpg)
>* Includes:
>   * Carrier Desination: Tube name used through all platforms, including BOLT simulation, consisted by "simple name" + "tube ID" + "tube thickness".
>   * Supplier Desination: Tube name used in supplier.
>   * Evap/Cond Type: Specify an evaporator or condenser type for tube used.
>   * More parameters are tube weight and dimension from obsoleted 17-19-23 C and D sections. Row 2 gives instructions, BOLT SWI also provides more detailed information.

* `FreshWaterSide:`
>![records](../../picture/TubeEDR/content-Freshwater.jpg)
>* Includes:
>   * Tube index TPDM calculation: Select proper index number for dedicated TPDM calculation method.  
>   * Reference documents: document source from 17-19-23 EDR and HTG files and supplier files.

* `BrineSide`
>![records](../../picture/TubeEDR/content-Brine.jpg)


* `Refrigerant_single`
>![records](../../picture/TubeEDR/content-refrigerantSingle.jpg)
>* Includes:
>   * Carrier Desination: Remove tube thickness since it has no impact on refrigerant side performance.
>   * Refrigerant: Refrigerant side performance closely relies on refrgierant type.
>   * Bundle factors: A/B/C coefficients to help get bundle factors for single tube condenser type only.

* `Refrigerant_bundle`
>![records](../../picture/TubeEDR/content-refrigerantBundle.jpg)
>* Includes:
>   * Refrigerant(& bundle frame):Refrigerant side coefficients relies on refrgierant type and bundle frame.

* `HTG_single tube`
>![records](../../picture/TubeEDR/content-HTGsingle.jpg)
>* Includes:

Tips:
* Gaps identified in excel and old pdf EDR
* Missing tubes information
* More detailed information find in xxxx


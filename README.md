# **Estimates of Rotation Periods for Jupiter Trojans with the Zwicky Transient Facility Photometric Light Curves**

## **Overview**  
This repository provides a comprehensive analysis of the rotation periods for **216 Jupiter Trojans** using photometric observations from the **Zwicky Transient Facility (ZTF)**. The analysis focuses on the determination of rotation periods, reliability flags, and additional parameters such as diameters and amplitude variations.  

**Note:** Due to the large file size, lightcurve plots are not included in this repository but can be provided upon request.

---

## **Repository Structure**  

- **/tables**  
  Contains the summary table (`Summary_Table.csv`), providing key details on the analyzed Jupiter Trojans, including rotation periods, reliability flags, amplitudes, and diameters.

---

## **Summary Table (Summary_Table.csv)**  
The summary table provides critical data for each Trojan, including:

- **Designation**: Unique identifier for each Jupiter Trojan.  
- **Best Period [hours]**: The rotation period determined from lightcurve analysis.  
- **Manual Period [hours]**: Period determined through manual verification.  
- **Reliability Flag**: Indicates the reliability of the period determination (1 = low, 3 = high).  
- **Total Observations**: Number of photometric data points used in the analysis.  
- **Amplitude**: Lightcurve amplitude, representing brightness variation.  
- **Diameter [km]**: Estimated diameter of the Trojan.

---

## **Lightcurve Plots (Available Upon Request)**  
Although the plots are not included due to file size constraints, they can be provided upon request. Each plot includes:

- **Panel A**: Corrected light curve for ZTF g and r band data.  
- **Panels B, C, D**: Phase-folded light curves for the most likely period, halved period, and doubled period, respectively.  
- **Panel E** *(if applicable)*: Phase-folded light curve using previously known periods.  
- **Panel F**: Lomb-Scargle periodogram showing the power of different periodicities and identifying the most likely period.  

If you wish to access these plots, please contact the repository owner directly.

---

## **Methodology**  

1. **Data Acquisition**  
   Photometric observations in the **g** and **r** bands were obtained from the **Zwicky Transient Facility (ZTF)** for each object.  

2. **Light Curve Pre-Processing**  
   Magnitudes were corrected for phase angle and distance effects to obtain intrinsic rotational light curves.  

3. **Rotation Period Determination**  
   The **Multi-Band Lomb-Scargle periodogram** was used to identify periodic signals and determine the most likely rotation period.  

4. **Manual Verification**  
   Phase-folded light curves were manually inspected to verify double-peaked profiles, and reliability flags were assigned accordingly.

---

## **Data Sources and Acknowledgements**  
Photometric data were sourced from the **Zwicky Transient Facility (ZTF)**. This research contributes to understanding the rotational properties and physical characteristics of Jupiter Trojans, offering insights into their formation and the dynamical history of the early Solar System.

---

## **Contact**  
For any questions, access to the light curve plots, or additional data requests, please contact:  
**Zhuofu (Chester) Li** at [zhuofu@uw.edu](mailto:zhuofu@uw.edu).

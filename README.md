# **Estimates of Jupiter Trojan Rotation Periods with Zwicky Transient Facility Lightcurves**

## **Overview**  
This repository provides a comprehensive analysis of the rotation periods for **216 Jupiter Trojans** using photometric observations from the **Zwicky Transient Facility (ZTF)**. The analysis focuses on the determination of rotation periods, reliability flags, and additional parameters such as diameters and amplitude variations.  

**Note:** Due to the large file size, light curve plots are not included in this repository but can be provided upon request.

---

## **Repository Structure**  

- **`Summary_Table.csv`**  
  Provides key details on the analyzed Jupiter Trojans, including rotation periods, reliability flags, amplitudes, and diameters.

---

## **Summary Table (Summary_Table.csv)**  
The summary table provides detailed data for each Jupiter Trojan, with the following columns:

- **Designation**: Unique identifier for each Jupiter Trojan.  
- **LCDB_Period [hours]**: Previously known rotation period from the Asteroid Lightcurve Database (LCDB), if available.  
- **Best_Period [hours]**: Rotation period determined through Lomb-Scargle periodogram analysis.  
- **Manual_Overwrite**: Period determined through manual inspection, if applicable.  
- **Reliability_Flag**: Value indicating the reliability of the period determination (1 = low, 3 = high).  
- **Comments**: Additional notes, including uncertainties or peculiarities observed during the analysis.  
- **#Minima**: Number of minima detected in the light curve, indicating possible rotation profiles.  
- **Chi2_g**: Chi-squared statistic for the fit of the g-band photometric data.  
- **Chi2_r**: Chi-squared statistic for the fit of the r-band photometric data.  
- **Avg_Chi2**: Average of the chi-squared values from g and r bands.  
- **N_obs_g**: Number of photometric observations in the g-band.  
- **N_obs_r**: Number of photometric observations in the r-band.  
- **Amplitude**: Measured amplitude of the light curve, representing brightness variation.  
- **Peak_Period**: Peak period identified in the Lomb-Scargle periodogram.  
- **Half_Period**: Half of the identified peak period, used to confirm double-peaked light curves.  
- **Twice_Period**: Twice the identified peak period, used to explore potential rotational harmonics.  
- **Diameter**: Estimated diameter of the Jupiter Trojan.  
- **Diameter_Unit**: Unit for the diameter measurement (typically in kilometers).

---

## **Light Curve Plots (Available Upon Request)**  
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

## **Future Work**  
These findings lay the groundwork for future analyses using data from the **Vera C. Rubin Observatory's Legacy Survey of Space and Time (LSST)**. LSST's deeper imaging and higher temporal cadence will enable the identification of rotational periods for smaller Trojans (down to ~1 km), refining our understanding of their spin barrier and density distributions.

---

## **How to Cite**  
If you use this dataset in your research, please cite it as:  

TBD

---

## **License**  
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## **Contact**  
For any questions, access to the light curve plots, or additional data requests, please contact:  
**Zhuofu (Chester) Li** at [zhuofu@uw.edu](mailto:zhuofu@uw.edu).

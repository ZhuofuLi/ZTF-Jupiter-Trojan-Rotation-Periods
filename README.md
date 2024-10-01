# Jupiter Trojans: Light Curve Analysis

## Overview
This repository provides a comprehensive analysis of the rotation periods for 216 Jupiter Trojans using photometric observations from the Zwicky Transient Facility (ZTF). The analysis includes detailed light curve plots for each object and a summary table that records the determined rotation periods, reliability flags, and additional parameters such as diameters and amplitude variations.

## Repository Structure
- **/plots**  
  Contains the light curve analysis plots for each of the 216 Jupiter Trojans. Each plot visualizes the corrected light curves, phase-folded curves for the most likely periods, and Lomb-Scargle periodograms.
  
- **/tables**  
  Contains the summary table (`Table_2.csv`) which provides details on the rotation periods, reliability flags, amplitude, and diameter of the analyzed Trojans.

- **/code (if applicable)**  
  Scripts used to perform the analysis, generate plots, and compile the summary table. Instructions on how to run the scripts and reproduce the analysis are provided.

## Summary Table (Table 2)
The summary table provides key data for each Trojan, including:
- **Designation**: The unique identifier for each Jupiter Trojan.
- **Best Period [hours]**: The determined rotation period based on light curve analysis.
- **Manual Period [hours]**: Period determined through manual verification.
- **Reliability Flag**: A value indicating the reliability of the period determination (1 = low, 3 = high).
- **Total Observations**: Number of photometric data points used in the analysis.
- **Amplitude**: Light curve amplitude representing brightness variation.
- **Diameter [km]**: Estimated diameter of the Trojan.

## Light Curve Analysis Plots
Each plot includes:
- **Panel A**: Corrected light curve for the ZTF g and r band data.
- **Panel B, C, D**: Phase-folded light curves for the most likely period, halved period, and doubled period, respectively.
- **Panel E (if applicable)**: Phase-folded light curve with previously known periods.
- **Panel F**: Lomb-Scargle periodogram showing the power of different periodicities and identifying the most likely period.

## Methodology
The following steps were followed to determine the rotation periods of Jupiter Trojans:
1. **Data Acquisition**: Photometric observations in the g and r bands were obtained from ZTF for each object.
2. **Light Curve Pre-Processing**: Corrected magnitudes for phase angle and distance effects to obtain intrinsic rotational light curves.
3. **Rotation Period Determination**: Used the Multi-Band Lomb-Scargle periodogram to search for periodic signals and identify the most likely rotation period.
4. **Manual Verification**: Phase-folded light curves were manually checked for double-peaked profiles indicative of asteroidal rotation and reliability flags were assigned.

## Data Sources and Acknowledgements
The light curves were derived from photometric observations obtained by the Zwicky Transient Facility (ZTF). This work contributes to understanding the rotational characteristics and physical properties of Jupiter Trojans, offering insights into their formation and the dynamics of the early solar system.

### References
- Bellm et al., 2019, [PASP, 131, 018002](https://doi.org/10.1088/1538-3873/aaecbe)
- Warner et al., 2009, [Icarus, 202, 134](https://doi.org/10.1016/j.icarus.2007.02.023)

## Future Work
These findings set the stage for further analysis using data from the upcoming Vera C. Rubin Observatory's Legacy Survey of Space and Time (LSST), which will enable more detailed and statistically significant studies of Jupiter Trojans and their rotational properties.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contact
For any questions or comments, please contact the repository owner, Zhuofu (Chester) Li, at zhuofuli@uw.edu.

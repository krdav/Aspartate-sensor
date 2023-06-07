# Cell line data and processing for jAspSnFR3 publication

This repository hosts the data, processing, analysis and plotting for the jAspSnFR3 manuscript titled:  
`An engineered biosensor enables dynamic aspartate measurements in living cells`

The sensor was tested by stable expression (lentivirus infection, monoclonal cell line) in different cell lines (H1299, HT1080 and HEK293T) and live cell imaged (GFP/RFP signal monitoring on Incucyte S3).
The sensor signal was captured using the GFP channel and normalized to RFP channel signal, using either RFP fused to the sensor, or a nuclear localized RFP.

Experiments were performed as either "temporal" (Figure 2 in manuscript) or "steady-state" (Figure 3 in manuscript).
With temporal experiments tracking sensor signal over time after a pertubation, and steady-state experiments correlating sensor signal with LCMS determined aspartate concentration after a pertubation has reached a near steady-state level of sensor signal.

Temporal data is read, analyzed and plotted here:  
`temporal_signal.ipynb`

Steady-state data is read, analyzed and plotted here:  
`steady-state_conc.ipynb`

For LCMS based amino acid quantification, isotope dilution was used and calibration curves generated. These calibration curves are plotted here:  
`AA_calibration-curves.pdf`




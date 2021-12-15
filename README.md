# Calibration of a SiPM spectrometer and determination of its resolution and efficiency at different energies
## Abstract
Gamma rays are typically originated from the decay of radioactive nuclei. Analysing the spectrum of a source is often useful to identify it, especially in astronomy. In this experiment the spectra of Am-241, Co-60, Cs-137 and Na-22 were analysed with a silicon photomultiplier (SiPM). Together with the SiPM, BGO, CsI and LYSO crystals were used. The optimal threshold voltage of each crystal was found, the spectrometer was calibrated and the efficiency and the resolution were determined. The efficiency and the resolution were found to decrease with energy. The calibration factors were found to be inversely proportional to the light yield of the crystal. A new set of measurement, with different settings, could improve the precision of the results. A more precise behavior of the resolution and the efficiency at different energies could be determined.

## Structure of the repository
.
├── README.md                                 # this file
├── analysis                                  # data analysis 
    ├── threshold.ipynb                       # thresholds and efficiencies
    ├── calibration.ipynb                     # calibration and resolution
    ├── GMA Data
        ├── Spectrum Data                     # spectra of sources
        ├── Threshold Determination Data      # counts at different thresholds
├── tex
    ├── main.pdf                              # report
    ├── ...

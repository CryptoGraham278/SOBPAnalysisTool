# SOBPAnalysisTool
Tool to analyze all pertinent information about Spread Out Bragg Peak data from OmniPro Incline (Zebra).

7 August 2017 - Chris Hertlein

Will be a test of my python skills to show that I can convert a Visual Basic / Excel Spreadsheet designed to analyze all relevant aspects of SOBP shots into quick and easily readable data for anyone to understand.

Desired features include:
=========================

- Input of the golden curve for the dataset used.
- Input of the exported CSV files directly from OmniPro Incline.
- Mass batch processing of all files and desired analysis.
- Choice of desired output information including JPG and output CSV files of easily readable information.
- Parsing of clinically accepted definitions: 
  - Range agreement (Distal 90?)
  - Modulation agreement (P90-D90 or P95-D95? Or any possible set of numbers)
- Ability to define noise floor and filter out noisy data from the Bragg peaks via a Peak2Skin rejection method.

Analysis features to include:
==============================

- Calculation of Distal Data:
  - Distal 95
  - Distal 90
  - Distal 80
  - Distal 50
  - Distal 20
  
- Calculation of Proximal Data:
  - Proximal 98
  - Proximal 95
  - Proximal 90
  - Proximal Modulation Dose
  
- Distal Penumbra/Fall-Off (D80-D20)
- Estimated Uniformity Region
- Flatness Calculation
- Tilt Calculation
- Dose at Modulation
- Range (D90)
- Modulation (P95-D95)

- Modulation Analysis:
  - Separation of all Bragg Peaks from SOBPs (layers):
  - Calculation of Proximal 90 of each BP (layer)
  - Calculation of Distal 90 of each BP (layer)
  - Calculation of Modulation Length per each additional BP (layer)

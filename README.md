# SatDataRetriever
SatDataRetriever 🛰️🌍 is a versatile Python-based tool designed to simplify the process of downloading satellite images from various sources. 

⚠️ Please Note:
1) Currently it contains a Jupyter notebook that allows users to download Sentinel-2 data at different processing levels (Level-1C and Level-2A), with detailed instructions and functions for setting up the region of interest, generating access tokens, and downloading images. 
2) There is a QGIS plugin called 'Sentinel 2 Image Downloader' that provides similar functionality with a simpler, no-code interface. 
💡 However, the main reason for writing this code was to record and log the unique identifiers of downloaded images. This is particularly useful for managing large batches and handling unstable internet connections. If the connection times out, the process can resume from where it left off using the generated CSV file. 
➕ Additionally, in rare cases, you may need to compare different baseline versions. To do this, you will need those images with varying baseline versions, which this code allows you to download. 
For instance 📌, this exact same image captured on 2021/10/05 (look at the file names below) has two baseline versions: N0300 and N0500 . A larger number indicates a more up-to-date version of the processing software.
👉 S2A_MSIL1C_20210520T235251_N0500_R130_T56JNQ_20230206T202338.SAFE
👉 S2A_MSIL1C_20210520T235251_N0300_R130_T56JNQ_20210521T012232.SAFE

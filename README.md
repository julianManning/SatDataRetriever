SatDataRetriever 🛰️🌍
SatDataRetriever is a versatile, Python-based tool designed to simplify the process of downloading public satellite imagery from various sources.
  
1)  🛰️ SatDataRetriever – Sentinel-2 Image Downloader
    SatDataRetriever is a Python-based tool designed to automate the download of Sentinel-2 satellite imagery from the Copernicus Data Space Ecosystem.  
    This is Perfect for time series analysis, environmental monitoring, and some large-scale Earth observation projects. The Jupyter notebook describe the code in great            detail.

    ✨ Key Features
    - 🔄 **Automatic token refresh** every 20 downloads
    - 🔁 **Retry logic** for 401 Unauthorized errors
    - ⏱️ **Download time tracking** per file
    - 📁 **Flexible ROI selection** (WKT, shapefile, or coordinates)
    - 📊 **CSV logging** for resumable sessions
    - 🌐 **Redirect URL support** for `.SAFE` files
    - 🧩 **Supports multiple baselines** of the same image
    - ⚙️ **Configurable timeout settings** for unstable connections
   
    🌍 Why Use SatDataRetriever?
    - Unlike plugin-based GIS tools (QGIS), SatDataRetriever offers:
    - Full **automation** for batch downloads
    - Easy **integration** into Python workflows
    - **Customizable** parameters for advanced use cases
    - **Resilience** against interrupted downloads

# ReVanced CLI Colab

A Google Colab setup for downloading and using the ReVanced CLI tool to patch Android APK files.

## Features
- Automatically fetches the latest versions of:
  - `revanced-cli` (command-line interface tool for patching).
  - `revanced-patches` (collection of patch definitions).
- Provides a simple interface to patch APK files using ReVanced.

## Requirements
- A Google account to access and run Google Colab.
- An APK file of the application you wish to patch.

## How to Use
1. **Open the Colab Notebook**  
   Upload the `revanced_cli.ipynb` notebook to your Google Drive or access it directly in Colab.

2. **Prepare Your APK File**  
   Upload the APK file of the application you wish to patch to your Colab workspace.

3. **Run the Notebook**  
   Execute the cells in sequence:
   - The first cell downloads the latest ReVanced CLI and patches files.
   - The second cell runs the patch command.

4. **Download the Patched APK**  
   Once patching is complete, download the patched APK file from the Colab workspace.

## Notes
- Ensure the APK file is compatible with ReVanced.
- You may need to adjust the patching command to specify the desired patches or additional options.

## Troubleshooting
- If you encounter any errors while fetching the latest versions, ensure your network connection is stable.
- Check the ReVanced [GitHub repository](https://github.com/ReVanced) for compatibility issues or updates.

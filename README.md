# Meshio Windows Standalone CLI

![Build Status](https://github.com/line2/pypkg/actions/workflows/build_exe.yml/badge.svg)

This repository provides a standalone **Windows Executable (`.exe`)** build for the popular [meshio](https://github.com/nschloe/meshio) library.

It allows you to convert mesh files (VTK, MSH, XDMF, OBJ, STL, etc.) on Windows **without needing to install Python or Pip**.

## 📥 Download

Go to the **[Releases Page](../../releases)** to download the latest `meshio-cli.exe`.

## 🚀 How to Use

### Method: Command Line (Recommended)
Open `PowerShell` or `CMD` in the folder where you downloaded the exe.

```powershell
# Check version
.\meshio-cli.exe --version

# Convert a file
.\meshio-cli.exe convert input.msh output.vtk

# Convert with compression
.\meshio-cli.exe convert input.msh output.xdmf --prune
```

## 🛠 Features

- **Standalone**: Single file, no dependencies required.
- **Full Support**: Built with `meshio[all]`, supporting NetCDF, HDF5, CGNS, and more.
- **Portable**: Can be run from a USB drive.


## ⚖️ License

This project is an unofficial build script.
The original `meshio` library is licensed under MIT.
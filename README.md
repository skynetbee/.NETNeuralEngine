# 🧠 .NETNeuralEngine

**.NETNeuralEngine** is a high-performance neural processing library packaged as a `.nupkg` file, designed for .NET developers building intelligent, ML-powered applications. It offers a clean and efficient API optimized for modern .NET environments.

## 🚀 Features

- Delivered as a `.nupkg` for seamless NuGet integration
- Supports **.NET Standard 2.0+** and **.NET 6+**
- Optimized for low-latency neural operations
- Works across platforms — Windows, Linux, macOS

## 📦 Installation

### 🔧 Manual Installation via `.nupkg`

1. Download the `.nupkg` file from the [**Releases**](https://github.com/skynetbee/.NETNeuralEngine/releases) section.

2. In **Visual Studio**:
   - Right-click your project > **Manage NuGet Packages**
   - Click the ⚙️ gear icon > select **Package Source: Local**
   - Add the folder where you saved the `.nupkg` file as a source
   - Search for `NeuralEngine` and install it

3. Or install via command line:

   ```bash
   dotnet add package NeuralEngine --source /path/to/local/folder ```
---
## Wire Up `DevEnv` in **`MainWindow`**

```cs
EngineStarter.DevEnv(this,
    new BlankPage1(),
    new BlankPage2(), 
    new BlankPage3(),
    new BlankPage4(), 
    new BlankPage5(),
    new BlankPage6(),
    new BlankPage7(),
    new BlankPage8(),
    new BlankPage9(),
    new BlankPage10(),
    new WorkAround()); ```

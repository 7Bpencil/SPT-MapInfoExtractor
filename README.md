```
Instructions were written for EFT 0.16.9.40087 and AssetRipper 1.3.14
```
 1. Compile the project in Release mode in IDE of your choise or open project folder in command line and type `dotnet build -c Release`
 2. Create an `Extract` folder in `bin\Release\net6.0\`
 3. Launch [AssetRipper](https://github.com/AssetRipper/AssetRipper/releases)
    - click `File -> Open Folder` and select `EscapeFromTarkov_Data\StreamingAssets\Windows\maps`
    - click `Export -> Export All Files -> Select Folder`
    - select `Extract` folder you created earlier and click `Export Unity Project`
    - click `File -> Open File` and select `EscapeFromTarkov_Data\globalgamemanagers`
    - click `View -> Search`, type `BuildSettings`, click `Search` and click on `BuildSettings` name
    - click on `Yaml` tab, scroll down and click `Save` into `Extract\ExportedProject\ProjectSettings` folder
 4. Run `DrakiaXYZ-MapInfoExtractor` executable
 5. Result will be stored in `maps.json`

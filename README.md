# MediaPipeSimPanel

## Build

### Windows (Visual Studio / MSBuild)

```powershell
msbuild .\MediaPipeSimPanel.slnx /p:Configuration=Debug /p:Platform=x64
```

or open `MediaPipeSimPanel.slnx` in Visual Studio and build from the IDE.

## Notes

- This project is currently Windows-only.
- Build system is `.slnx` + `.vcxproj` (MSBuild).
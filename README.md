# UNHEARD

A game built with Unity (6000.5.5f1). This repository contains the Windows build.

## Requirements

- Windows 10 or 11 (64-bit)
- A GPU with DirectX 12 support

## How to play

1. Download this repository: click **Code → Download ZIP**, or clone it:
   ```bash
   git clone https://github.com/akhilmenon777/UNHEARD.git
   ```
2. Extract the ZIP if you downloaded one.
3. Open the `Windows` folder and run `UNHEARD.exe`.

Keep every file in the `Windows` folder together. The game needs `UNHEARD_Data`, `UnityPlayer.dll` and the other files next to the `.exe` to run.

If Windows SmartScreen shows a warning, click **More info → Run anyway**.

## Repository contents

```
Windows/
├── UNHEARD.exe               # Game executable
├── UNHEARD_Data/             # Game data and assets
├── UnityPlayer.dll           # Unity runtime
├── UnityCrashHandler64.exe   # Unity crash reporter
├── MonoBleedingEdge/         # Mono scripting runtime
├── D3D12/                    # DirectX 12 runtime components
└── dstorage*.dll             # DirectStorage libraries
```

## Author

Akhil Menon ([@akhilmenon777](https://github.com/akhilmenon777))

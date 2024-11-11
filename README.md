# LDW Prototype
Unreal Engine module contains common prototyping stuff that will help you prototype ideas faster, including:
- Basic widgets like button, header, text input field.
- Grid-based materials.
## Requirements
No requirements needed.
## How to Use
- Download the module, extract it and place it in the `/Source/` directory of either your plugin or game module.
- Configure your plugin/module to use the module in `.Build.cs` and `.uplugin` or `.uproject`
```cpp
PublicDependencyModuleNames.AddRange(new string[] {
    "LDWPrototype"
});
```
```
"Modules": [
  {
    "Name": "LDWPrototype",
    "Type": "Runtime",
    "LoadingPhase": "Default"
  }, 
]
```

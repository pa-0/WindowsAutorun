# WindowsAutorun
_WindowsAutorun_ manages startup on the Windows OS. The following controls have been implemented in the current version:
- Register - LOCAL_MACHINE
- Register - CURRENT_USER
- Start - Startup Folder

## How to use?

1. ### Connect the required module depending on the type of startup: 

  - ### Registry Startup Items 
    - `Autorun.Windows.Register.pas` 
  - ### Startup Folder 
    - `Autorun.Windows.StartupDir.pas` .
      
2. ### Next, Initialize a variable of type `IAutorunManager` with the required supported class and work with this interface.

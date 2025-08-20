# BuildCookRun Attempt

An attempt was made to build and cook the sample project using Unreal's Automation Tool:

```bash
./Engine/Build/BatchFiles/RunUAT.sh BuildCookRun -project=MCPGameProject/MCPGameProject.uproject -nop4 -cook -stage -archive
```

The command failed because the Unreal Engine `RunUAT.sh` script could not be found:

```
bash: ./Engine/Build/BatchFiles/RunUAT.sh: No such file or directory
```

Ensure that Unreal Engine 5.6 or later is installed and that the command is executed from the root of the engine installation. Once the engine is available, rerun the above command to build and cook the project.

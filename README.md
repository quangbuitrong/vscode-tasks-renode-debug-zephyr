# vscode-tasks-renode-debug-zephyr
create tasks renode for debug zephyrRTOS sample/hello_world with k64f machine emulated board

The file "nxp-k64f.resc" is the script file for run renode with the machine as k64f,
this file should be located in: "C:\Program Files\Renode\scripts\single-node\"

where are files located:
 - C:\Program Files\Renode\scripts\single-node\nxp-k64f.resc
 - ${zephyrWorkspaceRoot}\.vscode\launch.json
 - ${zephyrWorkspaceRoot}\.vscode\tasks.json
 - ${zephyrWorkspaceRoot}\.vscode\platform.resc


The value of "miDebuggerPath" in "launch.json" is the path of arm-zephyr-eabi-gdb, should be replace with actual path in your PC.


For more details, please follow the instructions provided by renode: https://renode.readthedocs.io/en/latest/debugging/vscode.html

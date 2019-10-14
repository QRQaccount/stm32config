# 这是一个基于vscode搭建STM32开发环境的基本配置
## 使用的工具
1. arm-none-eabi-gcc
2. openOCD
3. STM32CubeMx

## 注意C/C++插件配置
将STM32Cub3mx中生成的Makefile中的`C_DEFS =`下参数加入defines中，将`C_INCLUDES`下参数加入includePath中
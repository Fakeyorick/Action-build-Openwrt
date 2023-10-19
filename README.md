# Action-build-Openwrt
[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat&logo=github&label=LICENSE)](https://github.com/Fakeyorick/Action-build-Openwrt/blob/main/LICENSE)

Through GitHub Actions Building Lede firware [Lean's OpenWrt](https://github.com/coolsnowwolf/lede).
Credit P3TERX: https://github.com/P3TERX/Actions-OpenWrt/  
Credit KFERMercer: https://github.com/KFERMercer/OpenWrt-CI  
 
**Action Build Tips**
- Each yml file under `.github/workflows` folder is the action configuration for specific architecture.
- The workflow action trigger is set by action workflow_dispatch manually.
- Default lan ip is supposed to be changed in the `[customize.sh]`.
# AXION AOSP QUASIS 2.6 
---
## GMS CORE VERSION
  - **UNOFFICIAL BETA BUILD by Localhorst04**
---

## Device Changelog
- Make use of new Axion 2.6 perf config
- Adjust UDFPS Animation size and offset values
- Add Restart SystemUI instead of Restart Fastboot
- Fix FP unlock animation bug

  **Issues**
  - Expanded QS-Tiles sometimes look funny

---

## Source Changelog

**AxionOS Version**: 2.6 QUASIS
**Security Patch:** April 2026


### What new in 2.6?
- **Fixed and improved dynamic bar issues**
  - new lockscreen media layout
  - remove redundant notification events override
  - connected pipeline to default status bar chip 
     - call chip should now show aosp calls ui
     - recording now uses default ui
- **Introduce AxBurstEngine v2**
  - improved performance engine with new framework and features
     - advanced thermal mitigation
     - ui first manager
     - BSP level boostings
- **Gamespace Improvements**
  - improved ui/ux
- **Edgelauncher improvements**
  - fixed reported issues
  - added default launch mode setting *(ct: Saikrishna1504)*
  - ui cleanup
- **Spoofing improvements**
  - fixed /data/adb exposure & regressions
- **AxPcMode Improvements**
  - layout fixes and ui improvements
- **AxionFx Improvements**
  - fixed effects not working on devices that use newer audio aidl like pixel 8/9/10 above *(ct: Corazon404)*
  - added device profiles
- **Pulse Launcher improvements**
  - fixed private/work profile issues
  - added guide for private space access on all apps drawer
  - added long press to organize folders for smart drawer layout
- **Routines improvements**
  - fixed not working routines
  - added http/internet routines
- **Improved activity animations**
  - new activity slide material expressive animation
- **New QS Tiles**
  - routines tiles
  - dns tiles
- **New Theme Store Themes**
  - added udfps icons
  - added udfps themes
- **Misc fixes**
  - fixed most issues reported in issue tracker
  - fixed performance issues on mid range soc like mtk dimensity 7200 pro
  - fixed lags when scrolling/flinging on unity games
  - fixed doze issues *(ct: bijoyv9)*
---

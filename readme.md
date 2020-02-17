Deprecated as nvidia support has ceased for macOS

***Strictly for PA70s with disableable Intel GPU (Choose discrete in BIOS), the setup documented in this repository WILL NOT work with *MSHybrid*, you will have to generate your own DSDT / SSDT in that case, ALTER CONFIG AS NEEDED***


<br>**Use USB 2.0 While Installing**
<br>**Do NOT use Lilu and its Plugins While Installing**
<br>**Use AptioMemoryFix3**

**Hackintosh Files for Clevo PA70, Kabylake only**

**Things that are pRoBleMatIc**
<br>Thunderbolt
<br>Card Reader</br>


**BIOS Settings:**
<br>TPM Enabled
<br>Graphics set to discrete only
<br>Quick boot set to On
<br>Thunderbolt Security set to legacy
<br>VT-d set to On</br>

**DSDT Patches Applied:**
N/A

**SSDT Patches Applied:**
<br>USBInjectAll SSDT
<br>CPU Power Management SSDT</br>

**Kexts Required:**
<br>ACPIBatteryManager.kext
<br>AppleALC.kext
<br>ApplePS2SmartTouchPad.kext
<br>CPUFriend.kext (Not required)
<br>FakePCIID_XHCIMux.kext (Not required)
<br>FakePCIID.kext (Not required)
<br>FakeSMC_ACPISensors.kext
<br>FakeSMC_CPUSensors.kext
<br>FakeSMC_GPUSensors.kext
<br>FakeSMC_LPCSensors.kext
<br>FakeSMC.kext
<br>Lilu.kext
<br>NoTouchID.kext
<br>RealtekRTL8111.kext
<br>USBInjectAll.kext
<br>WhateverGreen.kext</br>

**Kexts-to-Patch Applied:**
~~Raise USB Port Limit for 10.13.6~~ No need

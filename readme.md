***Strictly for PA70s with disableable Intel GPU (Choose discrete in BIOS), this will not work with Intel GPU, you will have to generate your own DSDT / SSDT in that case, ALTER CONFIG AS NEEDED***

**Hackintosh Files for Clevo PA70, Kabylake only**

<br>*BIOS Settings:*</br>
<br>TPM Enabled
<br>Graphics set to discrete only
<br>Quick boot set to On
<br>Thunderbolt Security set to legacy
<br>VT-d set to On</br>

<br>*DSDT Patches Applied:*</br>
N/A

<br>*SSDT Patches Applied:*</br>
<br>USBInjectAll SSDT
<br>CPU Power Management SSDT</br>

<br>*Kexts Required:*</br>
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

<br>*Kexts-to-Patch Applied:*</br>
<br>Raise USB Port Limit for 10.13.6</br>

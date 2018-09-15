**Hackintosh Files for Clevo PA70, Kabylake only**

<br>*BIOS Settings:*</br>
<br>TPM Enabled</br>
<br>Graphics set to discrete only</br>
<br>Quick boot set to On</br>
<br>Thunderbolt Security set to legacy</br>
<br>VT-d set to On</br>

<br>*DSDT Patches Applied:*</br>
N/A

<br>*SSDT Patches Applied:*</br>
USBInjectAll SSDT
CPU Power Management SSDT

<br>*Kexts Required:*</br>
ACPIBatteryManager.kext
AppleALC.kext
ApplePS2SmartTouchPad.kext
CPUFriend.kext (Not required)
FakePCIID_XHCIMux.kext (Not required)
FakePCIID.kext (Not required)
FakeSMC_ACPISensors.kext
FakeSMC_CPUSensors.kext
FakeSMC_GPUSensors.kext
FakeSMC_LPCSensors.kext
FakeSMC.kext
Lilu.kext
NoTouchID.kext
RealtekRTL8111.kext
USBInjectAll.kext
WhateverGreen.kext

<br>*Kexts-to-Patch Applied:*</br>
Raise USB Port Limit for 10.13.6

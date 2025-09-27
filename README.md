# WPR / [Procmon](https://github.com/5Noxi/wpr-reg-records/blob/main/promon/tracing.md) Registry Activity Records

Records were made while using `24H2` / `IoT Enterprise LTSC 2024`- Subkeys are always included. Most activities were recorded during boot, there are some others, such as `Steam.txt`, `TLOU2.txt`, `StartAllBack.txt`, and `Lighshot.txt`, that were traced using Procmon during use. WPR is included in WADK:
```ps
winget install Microsoft.WindowsADK
```
- [Windows Performance Recorder](https://learn.microsoft.com/en-us/windows-hardware/test/wpt/windows-performance-recorder)  
- [Process Monitor](https://learn.microsoft.com/en-us/sysinternals/downloads/procmon) ([*](https://live.sysinternals.com/))

Guide on how to trace registry activity for a specific app - [procmon.md](https://github.com/5Noxi/wpr-reg-records/blob/main/promon/tracing.md).

## Records Table

| File | Path(s) |
|------|---------|
| [ACPI.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/ACPI.txt) | `HKLM\SYSTEM\ControlSet001\Services\ACPI`<br>`HKLM\SYSTEM\ControlSet001\Services\acpiex`<br>`HKLM\SYSTEM\ControlSet001\Services\AcpiDev`<br>`HKLM\SYSTEM\ControlSet001\Services\acpipagr`<br>`HKLM\SYSTEM\ControlSet001\Services\AcpiPmi`<br>`HKLM\SYSTEM\ControlSet001\Services\acpitime` |
| [AFD-Parameters.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/AFD-Parameters.txt) | `HKLM\SYSTEM\ControlSet001\Services\AFD\Parameters` |
| [Accessibility.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Accessibility.txt) | `HKCU\Control Panel\Accessibility` |
| [Audio.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Audio.txt) | `HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Audio` |
| [BFE.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/BFE.txt) | `HKLM\SYSTEM\ControlSet001\Services\BFE` |
| [BrokerInfrastructure.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/BrokerInfrastructure.txt) | `HKLM\SYSTEM\ControlSet001\Services\BrokerInfrastructure` |
| [CV-Explorer.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/CV-Explorer.txt) | `HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer` |
| [Classpnp.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Classpnp.txt) | `HKLM\SYSTEM\ControlSet001\Control\Classpnp` |
| [Control-Wdf.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Control-Wdf.txt) | `HKLM\SYSTEM\ControlSet001\Control\Wdf` |
| [ControlPanel-Desktop.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/ControlPanel-Desktop.txt) | `HKCU\Control Panel\Desktop` |
| [ControlPanel-Mouse.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/ControlPanel-Mouse.txt) | `HKCU\Control Panel\Mouse` |
| [CrashControl.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/CrashControl.txt) | `HKLM\SYSTEM\ControlSet001\Control\CrashControl` |
| [Cryptography.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Cryptography.txt) | `HKLM\SOFTWARE\Microsoft\Cryptography` |
| [Disk-Storport-(990Pro).txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Disk-Storport-(990Pro).txt) | `HKLM\SYSTEM\ControlSet001\Enum\SCSI\Disk&Ven_NVMe&Prod_Samsung_SSD_990\5&33c33320&0&000000\Device Parameters\StorPort` (your path will be different) |
| [Dnscache-Parameters.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Dnscache-Parameters.txt) | `HKLM\SYSTEM\ControlSet001\Services\Dnscache\Parameters` |
| [Enum-USB.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Enum-USB.txt) | `HKLM\SYSTEM\ControlSet001\Enum\USB` |
| [Error-Reporting.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Error-Reporting.txt) | `HKLM\SOFTWARE\Microsoft\WINDOWS\Windows Error Reporting` |
| [FileSystem.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/FileSystem.txt) | `HKLM\SYSTEM\ControlSet001\Control\FileSystem` |
| [GRE-INITIALIZE.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/GRE-INITIALIZE.txt) | `HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\GRE_INITIALIZE` |
| [Graphics-Drivers.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Graphics-Drivers.txt) | `HKLM\SYSTEM\ControlSet001\Control\GraphicsDrivers` |
| [Input.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Input.txt) | `HKLM\SYSTEM\INPUT` |
| [Intel-00XX.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Intel-00XX.txt) | `HKLM\SYSTEM\ControlSet001\Control\Class\{4D36E968-E325-11CE-BFC1-08002BE10318}\00XX` (Intel) |
| [Intel.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Intel.txt) | `HKLM\Software\Intel` |
| [Internet-Settings.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Internet-Settings.txt) | `\Software\Microsoft\Windows\CurrentVersion\Internet Settings` |
| [LanmanServer.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/LanmanServer.txt) | `HKLM\SYSTEM\ControlSet001\Services\LanmanServer` |
| [Lighshot.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Lighshot.txt) | `HKCU\Software\SkillBrains\Lightshot` |
| [Lsa.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Lsa.txt) | `HKLM\SYSTEM\ControlSet001\Control\Lsa` |
| [MultiMedia.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/MultiMedia.txt) | `HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\MultiMedia` |
| [NDIS-Parameters.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/NDIS-Parameters.txt) | `HKLM\SYSTEM\ControlSet001\Services\NDIS\Parameters` |
| [NIC-Intel.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/NIC-Intel.txt) | `HKLM\SYSTEM\ControlSet001\Control\Class\{4d36e972-e325-11ce-bfc1-08002be10318}\00XX` (Intel) |
| [NVIDIA-DispGUID.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/NVIDIA-DispGUID.txt) | `HKLM\SYSTEM\ControlSet001\Control\Class\{4d36e968-e325-11ce-bfc1-08002be10318}\00XX` |
| [NVIDIA-Corp.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/NVIDIA-Corp.txt) | `HKLM\SOFTWARE\NVIDIA Corporation` |
| [NlaSvc.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/NlaSvc.txt) | `HKLM\SYSTEM\ControlSet001\Services\NlaSvc` |
| [OLE.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/OLE.txt) | `HKLM\SOFTWARE\Microsoft\OLE` ([*](https://learn.microsoft.com/en-us/windows/win32/com/hkey-local-machine-software-microsoft-ole)) |
| [PnP.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/PnP.txt) | `HKLM\SYSTEM\ControlSet001\Control\PnP` |
| [Policies-System.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Policies-System.txt) | `HKLM\SOFTWARE\Policies\Microsoft\WINDOWS\SYSTEM` |
| [Policies.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Policies.txt) | `HKLM\SYSTEM\ControlSet001\Policies` |
| [Policies.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/CV-Policies.txt) | `HKLM\Software\Microsoft\Windows\CurrentVersion\Policies` |
| [Power.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Power.txt) | `HKLM\SYSTEM\ControlSet001\Control\Power` |
| [Session-Manager.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Session-Manager.txt) | `HKLM\SYSTEM\ControlSet001\Control\Session Manager`<br>`HKLM\SYSTEM\ControlSet001\Control\Session Manager\Memory Management`<br>`HKLM\SYSTEM\ControlSet001\Control\Session Manager\Power`<br>`HKLM\SYSTEM\ControlSet001\Control\Session Manager\Quota System` |
| [StartAllBack.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/StartAllBack.txt) | `HKCU\Software\StartIsBack` |
| [Steam.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Steam.txt) | `HKCU\Software\Valve\Steam` |
| [StorPort.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/StorPort.txt) | `HKLM\SYSTEM\ControlSet001\Control\StorPort` |
| [TLOU2.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/TLOU2.txt) | `HKCU\Software\Naughty Dog` |
| [Tcpip-Parameters.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Tcpip-Parameters.txt) | `HKLM\SYSTEM\ControlSet001\Services\Tcpip\Parameters` |
| [Terminal-Server.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Terminal-Server.txt) | `HKLM\SYSTEM\ControlSet001\Control\Terminal Server` |
| [USB-Flags.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/USB-Flags.txt) | `HKLM\SYSTEM\ControlSet001\Control\usbflags` |
| [USBHUB3.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/USBHUB3.txt) | `HKLM\SYSTEM\ControlSet001\Services\USBHUB3` |
| [WHEA.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/WHEA.txt) | `HKLM\SYSTEM\ControlSet001\Control\WHEA` |
| [Windows-Defender.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Windows-Defender.txt) | `HKLM\SOFTWARE\Policies\Microsoft\Windows Defender` |
| [Windows-Dwm.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Windows-Dwm.txt) | `HKLM\SOFTWARE\Microsoft\Windows\Dwm` |
| [Winows-NT.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Winows-NT.txt) | `HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Windows` |
| [Wisp.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/Wisp.txt) | `HKCU\Software\Microsoft\Wisp` |
| [disk.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/disk.txt) | `HKLM\SYSTEM\ControlSet001\Services\disk` |
| [kbdclass.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/kbdclass.txt) | `HKLM\SYSTEM\ControlSet001\Services\kbdclass` |
| [kbdhid.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/kbdhid.txt) | `HKLM\SYSTEM\ControlSet001\Services\kbdhid` |
| [monitor.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/monitor.txt) | `HKLM\SYSTEM\ControlSet001\Services\monitor` |
| [mouclass.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/mouclass.txt) | `HKLM\SYSTEM\ControlSet001\Services\mouclass` |
| [mouhid.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/mouhid.txt) | `HKLM\SYSTEM\ControlSet001\Services\mouhid` |
| [nvlddmkm.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/nvlddmkm.txt) | `HKLM\SYSTEM\ControlSet001\Services\nvlddmkm` |
| [pci.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/pci.txt) | `HKLM\SYSTEM\ControlSet001\Enum\pci` |
| [stornvme.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/stornvme.txt) | `HKLM\SYSTEM\ControlSet001\Services\stornvme\Parameters` |
| [usbhub.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/usbhub.txt) | `HKLM\SYSTEM\ControlSet001\Services\usbhub` |
| [wbem.txt](https://github.com/5Noxi/wpr-reg-records/blob/main/records/wbem.txt) | `HKLM\SOFTWARE\Microsoft\wbem` |

## Kernel Values

Since many people don't yet know which values exist and what default value they have, here's a list. I used IDA, WinDbg, WinObjEx, Windows Internals E7 P1 to create it. The values are located in `\Machine\SYSTEM\CCS\Control\Session Manager\Kernel`.

- [Windows Internels E7](https://github.com/5Noxi/windows-books/releases)  
- [WinObjEx64](https://github.com/hfiref0x/WinObjEx64)  
- [WinDbg](https://learn.microsoft.com/en-us/windows-hardware/drivers/debugger/)  
- [Symbols Memory Dump](https://github.com/5Noxi/sym-mem-dump)  

`BoostingPeriodMultiplier`  
Default: `3`? (`KiNormalPriorityBoostingPeriodMultiplier dd 3`)  
  
  
`DefaultDynamicHeteroCpuPolicy`  
Default: `3` (Small)  
Meaning: Behavior of Dynamic hetero policy All (0) (all available) Large (1) LargeOrIdle (2) Small (3) SmallOrIdle (4) Dynamic (5) (use priority and other metrics to decide) BiasedSmall (6) (use priority and other metrics, but prefer small) BiasedLarge (7)  
  
  
`DefaultHeteroCpuPolicy`  
Default: `5` (`KiDefaultHeteroCpuPolicy dd 5`)  
  
  
`DynamicHeteroCpuPolicyExpectedRuntime`  
Default: `5200` (`KiDynamicHeteroCpuPolicyExpectedRuntime dd 1450h`)  
  
  
`DynamicHeteroCpuPolicyImportant`  
Default: `2` (LargeOrIdle)  
Meaning: Policy for a dynamic thread that is deemed important.  
  
  
`DynamicHeteroCpuPolicyImportantPriority`  
Default: `8` (`KiDynamicHeteroCpuPolicyImportantPriority dd 8`)  
Meaning: Priority above which threads are considered important if prioritybased dynamic policy is chosen.  
  
  
`DynamicHeteroCpuPolicyImportantShort`  
Default: `3` (Small)  
Meaning: Policy for dynamic thread that is deemed important but run a short amount of time.  
  
  
`DynamicHeteroCpuPolicyMask`  
Default: `7` (foreground status = 1, priority = 2, expected run time = 4)  
Meaning: Determine what is considered in assessing whether a thread is important.  
  
  
`ReadyTimeTicks`  
Default `6`?  
```c  
if ( (int)RtlQueryImageFileKeyOption(KeyHandle, 4, 0LL) >= 0 )  
{  
  if ( (unsigned int)KiNormalPriorityBoostReadyTimeTicks >= 6 )  
  {  
    if ( (unsigned int)KiNormalPriorityBoostReadyTimeTicks > 0x46 )  
      KiNormalPriorityBoostReadyTimeTicks = 70;  
  }  
  else  
  {  
    KiNormalPriorityBoostReadyTimeTicks = 6;  
  }  
}  
  
KiNormalPriorityBoostReadyTimeTicks dd 6  
  
lkd> dd KiNormalPriorityBoostReadyTimeTicks l1  
fffff806`c25c30c8  00000006  
```  
  
  
`ReservedCpuSets`  
Default: `0`  
```c  
lkd> dd kiReservedCpuSets l1  
fffff806`c25c66e0  00000000  
```  
  
  
`ScanLatencyTicks`  
Default: `7`?  
```c  
KiNormalPriorityBoostScanLatencyTicks dd 7  
  
lkd> dd KiNormalPriorityBoostScanLatencyTicks l1  
fffff806`c25c30c4  00000007  
```  
  
  
`SeTokenSingletonAttributesConfig`  
Default: `3`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aSetokensinglet ; "SeTokenSingletonAttributesConfig"  
dq offset SepTokenSingletonAttributesConfig  
  
lkd> dd SepTokenSingletonAttributesConfig l1  
fffff806`c24672c0  00000003  
```  
  
  
`ThreadReadyCount`  
Default: `1`? (`KiNormalPriorityBoostMaximumThreadReadyCount dd 1`)  
  
  
`DriveRemappingMitigation`  
Default: `1` (`ObpDriveRemappingMitigation dd 1`)  
  
  
`DPCTimeout`  
Default: `20000`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aDpctimeout   ; "DPCTimeout"  
dq offset KeDpcTimeoutMs  
  
KeDpcTimeoutMs  dd 4E20h  
```  
  
  
`DpcSoftTimeout`  
Default: `20000`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aDpcsofttimeout ; "DpcSoftTimeout"  
dq offset KeDpcSoftTimeoutMs  
  
KeDpcSoftTimeoutMs dd 4E20h  
```  
  
  
`DpcCumulativeSoftTimeout`  
Default: `120000` (`KeDpcCumulativeSoftTimeoutMs dd 1D4C0h`)  
  
  
`DpcWatchdogPeriod`  
Default: `120000` (`KeDpcWatchdogPeriodMs dd 1D4C0h`)  
  
  
`DpcWatchdogProfileOffset`  
Default: `10000`  
```c  
lkd> dd KeDpcWatchdogProfileOffsetMs l1  
fffff806`c25c4fd0  00002710  
```  
  
`DpcWatchdogProfileBufferSizeBytes`  
Default: `266240`  
```c  
lkd> dd KeDpcWatchdogProfileBufferSizeBytes l1  
fffff806`c25c304c  00041000  
```  
  
  
`DpcWatchdogProfileSingleDpcThreshold`  
Default: `18333`  
```c  
lkd> dd KeDpcWatchdogProfileSingleDpcThresholdMs l1  
fffff806`c25c3030  0000479d  
```  
  
  
`DpcWatchdogProfileCumulativeDpcThreshold`  
Default: `110000`  
```c  
lkd> dd KeDpcWatchdogProfileCumulativeDpcThresholdMs l1  
fffff806`c25c302c  0001adb0  
```  
  
  
`AmdTprLowerInterruptDelayConfig`  
Default: `0` (`KiAmdTprLowerInterruptDelayConfig dd 0`)  
  
  
`VerifierDpcScalingFactor`  
Default: `1` (`KeVerifierDpcScalingFactor dd 1`)  
  
  
`ThreadDpcEnable`  
Default: `1` (`KeThreadDpcEnable dd 1`  
  
  
`DpcQueueDepth`  
Default: `4`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aDpcqueuedepth ; "DpcQueueDepth"  
dq offset KiMaximumDpcQueueDepth  
KiMaximumDpcQueueDepth dd 4  
```  
  
  
`MinimumDpcRate`  
Default: `3` (`KiMinimumDpcRate dd 3`)  
  
  
`MaximumSharedReadyQueueSize`  
Default: `260` (`KiMaximumSharedReadyQueueSize dd 104h`)  
  
  
`MaximumCooperativeIdleSearchWidth`  
Default: `16` (`KiMaximumCooperativeIdleSearchWidth dd 10h`)  
  
  
`AdjustDpcThreshold`  
Default: `20` (`KiAdjustDpcThreshold dd 14h`)  
  
  
`PassiveWatchdogTimeout`  
Default: `300` (`KiPassiveWatchdogTimeout dd 12Ch`)  
  
  
`SchedulerAssistThreadFlagOverride`  
Default: `0` (`KiSchedulerAssistThreadFlagOverride dd 0`)  
  
  
`SerializeTimerExpiration`  
Default: `1` (`KiSerializeTimerExpiration dd 1`)  
Range: `0`-`2`  
"This behavior is controlled by the kernel variable KiSerializeTimerExpiration, which is initialized based on a registry setting whose value is different between a server and client installation. By modifying or creating the value SerializeTimerExpiration under HKLM\SYSTEM\CurrentControlSet\Control\Session Manager\kernel other than 0 or 1, serialization can be disabled, enabling timers to be distributed among processors. Deleting the value, or keeping it as 0, allows the kernel to make the decision based on Modern Standby availability, and setting it to 1 permanently enables serialization even on non-Modern Standby systems."  
  
  
`GlobalTimerResolutionRequests`  
Default: `0` (`KiGlobalTimerResolutionRequests dd 0`)  
  
  
`DisableLowQosTimerResolution`  
Default: `1` (`KeDisableLowQosTimerResolution db 1`)  
  
  
`EnablePerCpuClockTickScheduling`  
Default: `0`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aEnablepercpucl ; "EnablePerCpuClockTickScheduling"  
dq offset KiEnableClockTimerPerCpuTickScheduling  
  
KiEnableClockTimerPerCpuTickScheduling dd 0  
```  
  
  
`EnableTickAccumulationFromAccountingPeriods`  
Default: `0` (`KiEnableTickAccumulationFromAccountingPeriods dd 0`)  
  
  
`DisableTsx`  
Default: `0` (`KiDisableTsx    dd 0`)  
  
  
`VpThreadSystemWorkPriority`  
Default: `30` (`KiVpThreadSystemWorkPriority dd 1Eh`  
  
  
`PerfIsoEnabled`  
Default: `0` (`KiPerfIsoEnabled dd 0`)  
  
  
`CacheIsoBitmap`  
Default: `0` (`KiCacheIsoBitmap dd 0`)  
  
  
`IdealDpcRate`  
Default: `20` (`KiIdealDpcRate  dd 14h`)  
  
  
`CacheErrataOverride`  
Default: `0`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aCacheerrataove ; "CacheErrataOverride"  
dq offset KiTLBCOverride  
  
KiTLBCOverride  dd 0  
```  
  
  
`MaxDynamicTickDuration`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aMaxdynamictick ; "MaxDynamicTickDuration"  
dq offset KiMaxDynamicTickDuration  
dq offset KiMaxDynamicTickDurationSize  
KiMaxDynamicTickDurationSize db    8  
```  
  
  
`DisableExceptionChainValidation`  
Default: `2`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aDisableexcepti ; "DisableExceptionChainValidation"  
dq offset PspSehValidationPolicy  
PspSehValidationPolicy dd 2  
```  
  
  
`MitigationOptions`  
Default: `0`  
```c  
lkd> dd PspSystemMitigationOptions l1  
fffff806`c25c50f0  00000000  
```  
  
  
`MitigationAuditOptions`  
Default: `0`  
```c  
lkd> dd PspSystemMitigationAuditOptions l1  
fffff806`c25c5350  00000000  
```  
  
  
`DisableControlFlowGuardExportSuppression`  
Default: `0` (`PspDisableControlFlowGuardExportSuppression dd 0`)  
  
  
`ForceIdleGracePeriod`  
Default: `5` (`KiForceIdleGracePeriodInSec dd 5`)  
  
  
`HotpatchTestMode`  
Default: `0` (`KeHotpatchTestMode dd 0`)  
  
  
`ObTracePoolTags`  
Default: `0`  
```  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aObtracepooltag ; "ObTracePoolTags"  
dq offset ObpTracePoolTagsBuffer  
dq offset ObpTracePoolTagsLength  
  
lkd> dd ObpTraceProcessNameBuffer l1  
fffff806`c250d5c0  00000000  
```  
  
  
`ObTraceProcessName`  
Default: `0`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
Idq offset aObtraceprocess ; "ObTraceProcessName"  
dq offset ObpTraceProcessNameBuffer  
dq offset ObpTraceProcessNameLength  
  
lkd> dd ObpTraceProcessNameBuffer l1  
fffff806`c250d5c0  00000000  
```  
  
  
`ObTracePermanent`  
Default: `0`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aObtracepermane ; "ObTracePermanent"  
dq offset ObpTracePermanent  
  
lkd> dd ObpTracePermanent l1  
fffff806`c250d560  00000000  
```  
  
  
`PoCleanShutdownFlags`  
Default: `0`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aPocleanshutdow ; "PoCleanShutdownFlags"  
dq offset PopShutdownCleanly  
  
lkd> dd PopShutdownCleanly l1  
fffff806`c250a210  00000000  
```  
  
  
`ObUnsecureGlobalNames`  
Default: `6619246`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aObunsecureglob ; "ObUnsecureGlobalNames"  
dq offset ObpUnsecureGlobalNamesBuffer  
dq offset ObpUnsecureGlobalNamesLength  
  
lkd> dd ObpUnsecureGlobalNamesBuffer l1  
fffff806`c24662c0  0065006e  
```  
  
  
`TimerCheckFlags`  
Default: `1` (`KeTimerCheckFlags dd 1`)  
  
  
`SplitLargeCaches`  
Default: `0` (`KiSplitLargeCaches dd 0`)  
  
  
`AlwaysTrackIoBoosting`  
Default: `0` (`PspAlwaysTrackIoBoosting dd 0`)  
  
  
`ObCaseInsensitive`  
Default: `1`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aObcaseinsensit ; "ObCaseInsensitive"  
dq offset ObpCaseInsensitive  
  
lkd> dd ObpCaseInsensitive l1  
fffff806`c240b030  00000001  
```  
  
  
`BugCheckUnexpectedInterrupts`  
Default: `0`  
```c  
lkd> dd KiBugCheckUnexpectedInterrupts l1  
fffff806`c2465eec  00000000  
```  
  
  
`DebuggerIsStallOwner`  
Default: `0`  
```c  
lkd> dd KiDebuggerIsStallOwner l1  
fffff806`c2465f04  00000000  
```  
  
  
`DebugPollInterval`  
Default: `2000` (`KiDebugPollInterval dd 7D0h`)  
  
  
`PowerOffFrozenProcessors`  
Default: `1` (`KiPowerOffFrozenProcessors db    1`)  
  
  
`DisableLightWeightSuspend`  
Default: `0` (`KiDisableLightWeightSuspend dd 0`)  
  
  
`ObObjectSecurityInheritance`  
Default: `0`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aObobjectsecuri ; "ObObjectSecurityInheritance"  
dq offset ObpObjectSecurityInheritance  
  
lkd> dd ObpObjectSecurityInheritance l1  
fffff806`c24663c0  00000000  
```  
  
  
`SeAllowAllApplicationAceRemoval`  
Default: `0`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aSeallowallappl ; "SeAllowAllApplicationAceRemoval"  
dq offset SepAllowAllApplicationAceRemoval  
  
lkd> dd SepAllowAllApplicationAceRemoval l1  
fffff806`c25d6268  00000000  
```  
  
  
`HyperStartDisabled`  
Default: `0`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aHyperstartdisa ; "HyperStartDisabled"  
dq offset HvlVpStartDisabled  
  
lkd> dd HvlVpStartDisabled l1  
fffff806`c258cecc  00000000  
```  
  
  
`SeAllowSessionImpersonationCapability`  
Default: `0`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aSeallowsession ; "SeAllowSessionImpersonationCapability"  
dq offset SepAllowSessionImpersonationCap  
  
lkd> dd SepAllowSessionImpersonationCap l1  
fffff806`c25d6190  00000000  
```  
  
  
`InterruptSteeringFlags`  
Default: `0` (`1` Off / `2` On)  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aInterruptsteer ; "InterruptSteeringFlags"  
dq offset KiInterruptSteeringFlags  
  
lkd> dd KiInterruptSteeringFlags l1  
fffff806`c25c4cfc  00000000  
```  
  
  
`SeTokenSingletonAttributesConfig`  
Default: `3`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aSetokensinglet ; "SeTokenSingletonAttributesConfig"  
dq offset SepTokenSingletonAttributesConfig  
  
lkd> dd SepTokenSingletonAttributesConfig l1  
fffff803`d34672c0  00000003  
```  
  
  
`SeCompatFlags`  
Default: `0` (`SeCompatFlags   db    0`)  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aSecompatflags ; "SeCompatFlags"  
dq offset SeCompatFlags  
  
lkd> dd SeCompatFlags l1  
fffff803`d35d7e24  00000000  
```  
  
  
`SeTokenLeakDiag`  
Default: `0`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aSetokenleakdia ; "SeTokenLeakDiag"  
dq offset SeTokenLeakTracking  
  
lkd> dd SeTokenLeakTracking l1  
fffff803`d35d6010  00000000  
```  
  
  
`SeTokenDoesNotTrackSessionObject`  
Default: `0` (`SeTokenDoesNotTrackSessionObject dd 0`)  
  
  
`HeteroFavoredCoreFallback`  
Default: `0`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aHeterofavoredc ; "HeteroFavoredCoreFallback"  
dq offset PpmHeteroFavoredCoreFallback  
  
lkd> dd PpmHeteroFavoredCoreFallback l1  
fffff803`d35c5108  00000000  
```  
  
  
`VirtualHeteroHysteresis`  
Default: `4294967295`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aVirtualheteroh ; "VirtualHeteroHysteresis"  
dq offset PpmPerfQosTransitionHysteresisOverride  
  
lkd> dd PpmPerfQosTransitionHysteresisOverride l1  
fffff803`d35c3058  ffffffff  
```  
  
  
`WpsSimulationOverride`  
Default: `0`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aWpssimulationo ; "WpsSimulationOverride"  
dq offset PpmWpsSimulationOverride  
dq offset PpmWpsSimulationOverrideSize  
  
lkd> dd PpmWpsSimulationOverride l1  
fffff803`d35c5038  00000000  
```  
  
  
`RebalanceMinPriority`  
Default: `1` (`KiRebalanceMinPriority dd 1`)  
  
  
`SeLpacEnableWatsonReporting`  
Default: `0`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aSelpacenablewa ; "SeLpacEnableWatsonReporting"  
dq offset SeLpacEnableWatsonReporting  
  
lkd> dd SeLpacEnableWatsonReporting l1  
fffff803`d34670a4  00000000  
```  
  
  
`SeLpacEnableWatsonThrottling`  
Default: `1` (`SeLpacEnableWatsonThrottling dd 1`)  
  
  
`EnableWerUserReporting`  
Default: `1` (`DbgkEnableWerUserReporting dd 1`)  
  
  
`DeviceOwnerProtectionDowngradeAllowed`  
Default: `0`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aDeviceownerpro ; "DeviceOwnerProtectionDowngradeAllowed"  
dq offset SeDeviceOwnerProtectionDowngradeAllowed  
  
lkd> dd SeDeviceOwnerProtectionDowngradeAllowed l1  
fffff803`d34670a0  00000000  
```  
  
  
`CacheAwareScheduling`  
Default: `47` (`KiCacheAwareScheduling dd 2Fh`)  
  
  
`HeteroSchedulerOptions`  
Default: `0` (`KiHeteroSchedulerOptions dd 0`)  
  
  
`HeteroSchedulerOptionsMask`  
Default: `0` (`KiHeteroSchedulerOptionsMask dd 0`)  
  
  
`ForceForegroundBoostDecay`  
Default: `0`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aForceforegroun ; "ForceForegroundBoostDecay"  
dq offset KiSchedulerForegroundBoostDecayPolicy  
  
lkd> dd KiSchedulerForegroundBoostDecayPolicy l1  
fffff803`d35c309c  00000000  
```  
  
  
`ForceBugcheckForDpcWatchdog`  
Default: `0` (`KiForceBugcheckForDpcWatchdog dd 0`)  
  
  
`LongDpcRuntimeThreshold`  
Default: `100` (`KiLongDpcRuntimeThreshold dd 64h`)  
  
  
`LongDpcQueueThreshold`  
Default: `3` (`KiLongDpcQueueThreshold dd 3`)  
  
  
`HgsPlusFeedbackUpdateThresholdRuntime`  
Default: `20`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aHgsplusfeedbac ; "HgsPlusFeedbackUpdateThresholdRuntime"  
dq offset dword_140FC33B4  
  
dword_140FC33B4 dd 14h  
```  
  
  
`HgsPlusFeedbackUpdateThresholdNetRuntime`  
Default: `20`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aHgsplusfeedbac_0 ; "HgsPlusFeedbackUpdateThresholdNetRuntim"...  
dq offset dword_140FC33C  
  
dword_140FC33C0 dd 14h  
```  
  
  
`HgsPlusInvalidFeedbackLimit`  
Default: `50`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aHgsplusinvalid_1 ; "HgsPlusInvalidFeedbackLimit"  
dq offset dword_140FC33D0  
  
dword_140FC33D0 dd 32h  
```  
  
  
`HgsPlusInvalidFeedbackDefaultClass`  
Default: `0`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aHgsplusinvalid ; "HgsPlusInvalidFeedbackDefaultClass"  
dq offset dword_140FC33D4  
  
dword_140FC33D4 dd 0  
```  
  
  
`HgsPlusInvalidFeedbackDefaultClassSet`  
Default: `0`  
  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aHgsplusinvalid_0 ; "HgsPlusInvalidFeedbackDefaultClassSet"  
dq offset dword_140FC33D8  
  
dword_140FC33D8 dd 0  
```  
  
`HgsPlusLowerPerfClassFeedbackThreshold`  
Default: `4`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aHgspluslowerpe ; "HgsPlusLowerPerfClassFeedbackThreshold"  
dq offset dword_140FC33DC  
  
dword_140FC33DC dd 4  
```  
  
  
`HgsPlusHigherPerfClassFeedbackThreshold`  
Default: `1`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aHgsplushigherp ; "HgsPlusHigherPerfClassFeedbackThreshold"  
dq offset dword_140FC33E0  
  
dword_140FC33E0 dd 1  
```  
  
  
`HgsPlusMinimumScoreDifferenceForSwap`  
Default: `25`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aHgsplusminimum ; "HgsPlusMinimumScoreDifferenceForSwap"  
dq offset dword_140FC33E8  
  
dword_140FC33E8 dd 19h  
```  
  
  
`HgsPlusThreadCreationDefaultClass`  
Default: `0`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
q offset aHgsplusthreadc ; "HgsPlusThreadCreationDefaultClass"  
dq offset dword_140FC33E4  
  
dword_140FC33E4 dd 0  
```  
  
  
`DisablePointerParameterAlignmentValidation`  
Default: `0` (`KiDisablePointerParameterAlignmentValidation dd 0`)  
  
  
`XStateContextLookasidePerProcMaxDepth`  
Default: `0`  
```c  
dq offset aSessionManager_5 ; "Session Manager\\Kernel"  
dq offset aXstatecontextl ; "XStateContextLookasidePerProcMaxDepth"  
dq offset KiXStateContextLookasidePerProcMaxDepth  
  
lkd> dd KiXStateContextLookasidePerProcMaxDepth l1  
fffff803`d3520724  00000000  
```  
  
  
`IdealNodeRandomized`  
Default: `1` (`PspIdealNodeRandomized dd 1`)  
  
  
`ForceParkingRequested`  
  
  
`Session Manager\Kernel\RNG : RNGAuxiliarySeed`  
```c  
dq offset aSessionManager_0 ; "Session Manager\\Kernel\\RNG"  
dq offset aRngauxiliaryse ; "RNGAuxiliarySeed"  
dq offset ExpRNGAuxiliarySeed  
```  

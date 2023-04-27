        Realtek Semiconductor Corp. High Definition Audio System Software Ver:R2.14
                        Installation and Setup


Driver Installation/Removal Procedure For Realtek High Definition Audio Codec:
=================================================================================

<<< For Windows 2000/XP/Vista x86/x64 (WDM driver) >>>

---------------------------------------
Setup Driver at first time:
---------------------------------------
Windows 2000 , XP :
Step 1. Before installing the Realtek HD Audio Drivers, Press the
        [Cancel] button if Windows detect the Multimedia Audio device. 
          
Step 2. Run the setup.exe program to start the installation. 
  
Step 3. Click on [Next/OK/Go] to continue the procedure. If the Windows popup 
        "Digital Signature Not Found" message, press [Yes] to continue the 
        installation.
        
Step 4. Finally, select to restart the system and press [Finish] to complete
        the installation.  

Windows Vista :
Step 1. Run the setup.exe program to start the installation. 
  
Step 2. Click on [Next/OK/Go] to continue the procedure. If the Windows popup 
        "Windows can't verify the publisher of this driver software" message, 
        press "Install this driver software anyway" to continue the installation.
        
Step 3. Finally, select to restart the system and press [Finish] to complete
        the installation.  

--------------------------
Update Driver:
--------------------------
Windows 2000 , XP :
Step 1. Follow Step 2,3,4 described in [Setup at first time] above to complete
        the procedure.

Windows Vista :
Step 1. Run setup.exe, it will remove the original driver in your system.

Step 2. Click "Next" to remove the original audio driver in your system.

Step 3. Once after the original driver removed , reboot the computer.

Step 4. Please go back to the new driver package after computer restarted.

Step 5. Run setup.exe, it will install the new audio driver then.

--------------------------
Remove Driver:
--------------------------
Windows 2000 , XP :
Step 1. Go to Start\Settings\Control Panel.

Step 2. Select [Add/Remove Programs] icon.

Step 3. Select "Realtek HD Audio Drivers" and press [Change/Remove]
        button.

Step 4. Click on [Next/OK/Go] to finish the uninstallation.        

Step 5. At the end of the procedure, select to restart the system and press
        [Finish] to complete the uninstallation.

Windows Vista :
Step 1. Go to Start\Settings\Control Panel.

Step 2. Select [Programs] icon.

Step 3. Select [Programs and Features] icon.

Step 4. Select "Realtek HD Audio Drivers" and press [uninstall] button.

Step 5. Click on [Next/OK/Go] to finish the uninstallation.        

Step 6. At the end of the procedure, select to restart the system and press
        [Finish] to complete the uninstallation.


<< Other Informations >>

--------------------
Silent Installation:
--------------------

Run "Setup.exe /s /f2<path\LogFile> /z[-rp<path\LogFile>]"
i.e. setup.exe /s /f2c:\mylog.log /z[-rpC:\RHDSetup.log]

--------------------
Silent Uninstallation:
--------------------

Run "Setup.exe /removeonly /s /f1<path\USetup.iss> /f2<path\LogFile> /z[-rp<path\LogFile>]"
i.e. setup.exe /removeonly /s /f1C:\AudioDriver\USetup.iss /f2c:\mylog.log /z[-rpC:\RHDSetup.log]


Note: 1. Please update Directx version to DirectX8.1 or above.

---------------------
Version Informations:
---------------------
If driver package include below drivers :
-----------------------------------------------------------------------
Windows 2000/XP :
RTKHDA64.sys                                        : 5.10.0.5772
RTKHDAUD.sys                                        : 5.10.0.5772
Alcmtr.exe                                          : 1.6.0.3
AlcWzrd.exe                                         : 1.1.0.37
MicCal.exe                                          : 1.1.2.0
RTHDCPL.exe                                         : 2.2.5.9
RtkAudioService64.exe                               : 1.0.0.17
RtkAudioService.exe                                 : 1.0.0.16
RTLCPL.exe                                          : 1.0.1.66
RtlUpd64.exe                                        : 2.7.1.1
RtlUpd.exe                                          : 2.7.1.1
SkyTel.exe                                          : 2.0.2.0
SoundMan.exe                                        : 1.0.0.32
vncutil64.exe                                       : 1.0.0.23
vncutil.exe                                         : 1.0.0.23
AMBFilt64.sys                                       : 5.10.0.4240
AMBFilt.sys                                         : 5.10.0.4240
Monfilt64.sys                                       : 5.10.0.4115
Monfilt.sys                                         : 5.10.0.4112
ALSndMgr.cpl                                        : 1.0.0.11
RTSndMgr.cpl                                        : 1.0.1.0
RCoInst64XP.dll                                     : 1.0.4.4
RTCOMDLL.dll                                        : 1.0.0.97
RtkCoInstXP.dll                                     : 1.0.4.4
RtlCPAPI.dll                                        : 1.0.1.9

Vista driver : --------------------------------------------------------
Vista driver for x86
RTKVHDA.sys                                         : 6.0.1.5772
AERTSrv.exe                                         : 1.0.32.8
RtHDVCpl.exe                                        : 1.0.0.291
RtkAudioService.exe                                 : 1.0.0.17
RtlUpd.exe                                          : 2.7.1.1
SkyTel.exe                                          : 2.0.2.2
vncutil.exe                                         : 1.0.0.23
RTSndMgr.cpl                                        : 1.0.0.13
AERTACap.dll                                        : 2.0.32.1
AERTARen.dll                                        : 1.0.32.7
CTAPO32.dll                                         : 1.0.0.530
ctppld.dll                                          : 1.0.0.530
DaisyWrp.dll                                        : 1.0.0.70
FMAPO.dll                                           : 0.0.12.1
MaxxAudioAPO.dll                                    : 1.2.2.0
MaxxAudioAPO20.dll                                  : 2.2.2.0
MaxxAudioEQ.dll                                     : 5.9.7.0
ppchain.dll                                         : 1.0.0.70
RTCOMDLL.dll                                        : 2.0.0.105
RtkAPO.dll                                          : 11.0.6000.85
RtkApoApi.dll                                       : 1.0.0.9
RtkCfg.dll                                          : 1.0.0.1
RtkCoInst.dll                                       : 1.0.4.4
RtkPgExt.dll                                        : 6.0.6000.66
RtlCPAPI.dll                                        : 1.0.2.1
slcshp32.dll                                        : 1.0.3.0
slgeq32.dll                                         : 1.0.1.0
slh36032.dll                                        : 1.0.2.0
slInit32.dll                                        : 1.1.1.0
sltshd32.dll                                        : 1.1.0.0
sluapo32.dll                                        : 1.2.6.0
SRSHP360.dll                                        : 1.1.0.0
SRSTSHD.dll                                         : 1.1.4.0
SRSTSXT.dll                                         : 3.2.0.0
SRSWOW.dll                                          : 1.1.3.0
WavesLib.dll                                        : 5.9.7.0

Vista driver for x64
RTKVHD64.sys                                        : 6.0.1.5772
AERTSr64.exe                                        : 1.0.64.8
RAVCpl64.exe                                        : 1.0.0.291
RtkAudioService64.exe                               : 1.0.0.17
RtlUpd64.exe                                        : 2.7.1.1
SkyTel.exe                                          : 2.0.2.2
vncutil64.exe                                       : 1.0.0.23
GWfilt64.sys                                        : 6.10.0.3
RTSnMg64.cpl                                        : 1.0.0.13
AERTAC64.dll                                        : 2.0.64.1
AERTAR64.dll                                        : 1.0.64.7
CTAPO32.dll                                         : 1.0.0.530
CTAPO64.dll                                         : 1.0.0.530
ctppld.dll                                          : 1.0.0.530
DaisyWrp.dll                                        : 1.0.0.70
FMAPO64.dll                                         : 0.0.12.1
MaxxAudioAPO20.dll                                  : 2.2.2.0
ppchain.dll                                         : 1.0.0.70
RCoInst64.dll                                       : 1.0.4.4
RtCOM64.dll                                         : 2.0.0.105
RTCOMDLL.dll                                        : 2.0.0.105
RtkApi64.dll                                        : 1.0.0.9
RtkAPO64.dll                                        : 11.0.6000.85
RtkCfg.dll                                          : 1.0.0.1
RtkCfg64.dll                                        : 1.0.0.1
RtlCPAPI.dll                                        : 1.0.2.1
RtlCPAPI64.dll                                      : 1.0.2.1
RtPgEx64.dll                                        : 6.0.6000.66
slcshp64.dll                                        : 1.0.3.0
slgeq64.dll                                         : 1.0.1.0
slh36064.dll                                        : 1.0.2.0
slInit64.dll                                        : 1.1.1.0
sltshd64.dll                                        : 1.1.0.0
sluapo64.dll                                        : 1.2.6.0
SRSHP64.dll                                         : 1.1.0.0
SRSTSH64.dll                                        : 1.1.4.0
SRSTSX64.dll                                        : 3.2.0.0
SRSWOW64.dll                                        : 1.1.3.0


HDMI Driver : ---------------------------------------------------------
Vista x86:
RtHDMIV.sys                                         : 6.0.1.5766
RtkUpd.exe                                          : 2.7.1.1
RHCoInst.dll                                        : 1.0.3.2
RHDMIExt.dll                                        : 6.0.6000.66
RtkHDMI.dll                                         : 11.0.6000.85

Vista x64:
RtHDMIVX.sys                                        : 6.0.1.5766
RtkUpd64.exe                                        : 2.7.1.1
RHCoInst64.dll                                      : 1.0.3.2
RHDMEx64.dll                                        : 6.0.6000.66
RtkHDM64.dll                                        : 11.0.6000.85

XP/2K x86:
RtkHDMI.sys                                         : 5.10.0.5766
RtkUpd.exe                                          : 2.7.1.1

XP/2K x64:
RtHDMIX.sys                                         : 5.10.0.5766
RtkUpd64.exe                                        : 2.7.1.1


Driver Setup Program                                : 2.69

--------
History:
--------
Driver Package R2.14
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC665, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272, ALC273, ALC887
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC665, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272, ALC273, ALC887
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
            2. Change EAPD control method for the certain codecs.
     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5772
  RTKHDAUD.sys                                        : 5.10.0.5772
  Alcmtr.exe                                          : 1.6.0.3
  AlcWzrd.exe                                         : 1.1.0.37
  MicCal.exe                                          : 1.1.2.0
  RTHDCPL.exe                                         : 2.2.5.9
  RtkAudioService64.exe                               : 1.0.0.17
  RtkAudioService.exe                                 : 1.0.0.16
  RTLCPL.exe                                          : 1.0.1.66
  RtlUpd64.exe                                        : 2.7.1.1
  RtlUpd.exe                                          : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.32
  vncutil64.exe                                       : 1.0.0.23
  vncutil.exe                                         : 1.0.0.23
  AMBFilt64.sys                                       : 5.10.0.4240
  AMBFilt.sys                                         : 5.10.0.4240
  Monfilt64.sys                                       : 5.10.0.4115
  Monfilt.sys                                         : 5.10.0.4112
  ALSndMgr.cpl                                        : 1.0.0.11
  RTSndMgr.cpl                                        : 1.0.1.0
  RCoInst64XP.dll                                     : 1.0.4.4
  RTCOMDLL.dll                                        : 1.0.0.97
  RtkCoInstXP.dll                                     : 1.0.4.4
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5772
  AERTSrv.exe                                         : 1.0.32.8
  RtHDVCpl.exe                                        : 1.0.0.291
  RtkAudioService.exe                                 : 1.0.0.17
  RtlUpd.exe                                          : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.2
  vncutil.exe                                         : 1.0.0.23
  RTSndMgr.cpl                                        : 1.0.0.13
  AERTACap.dll                                        : 2.0.32.1
  AERTARen.dll                                        : 1.0.32.7
  CTAPO32.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO.dll                                           : 0.0.12.1
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.2.2.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  ppchain.dll                                         : 1.0.0.70
  RTCOMDLL.dll                                        : 2.0.0.105
  RtkAPO.dll                                          : 11.0.6000.85
  RtkApoApi.dll                                       : 1.0.0.9
  RtkCfg.dll                                          : 1.0.0.1
  RtkCoInst.dll                                       : 1.0.4.4
  RtkPgExt.dll                                        : 6.0.6000.66
  RtlCPAPI.dll                                        : 1.0.2.1
  slcshp32.dll                                        : 1.0.3.0
  slgeq32.dll                                         : 1.0.1.0
  slh36032.dll                                        : 1.0.2.0
  slInit32.dll                                        : 1.1.1.0
  sltshd32.dll                                        : 1.1.0.0
  sluapo32.dll                                        : 1.2.6.0
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5772
  AERTSr64.exe                                        : 1.0.64.8
  RAVCpl64.exe                                        : 1.0.0.291
  RtkAudioService64.exe                               : 1.0.0.17
  RtlUpd64.exe                                        : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.2
  vncutil64.exe                                       : 1.0.0.23
  GWfilt64.sys                                        : 6.10.0.3
  RTSnMg64.cpl                                        : 1.0.0.13
  AERTAC64.dll                                        : 2.0.64.1
  AERTAR64.dll                                        : 1.0.64.7
  CTAPO32.dll                                         : 1.0.0.530
  CTAPO64.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO64.dll                                         : 0.0.12.1
  MaxxAudioAPO20.dll                                  : 2.2.2.0
  ppchain.dll                                         : 1.0.0.70
  RCoInst64.dll                                       : 1.0.4.4
  RtCOM64.dll                                         : 2.0.0.105
  RTCOMDLL.dll                                        : 2.0.0.105
  RtkApi64.dll                                        : 1.0.0.9
  RtkAPO64.dll                                        : 11.0.6000.85
  RtkCfg.dll                                          : 1.0.0.1
  RtkCfg64.dll                                        : 1.0.0.1
  RtlCPAPI.dll                                        : 1.0.2.1
  RtlCPAPI64.dll                                      : 1.0.2.1
  RtPgEx64.dll                                        : 6.0.6000.66
  slcshp64.dll                                        : 1.0.3.0
  slgeq64.dll                                         : 1.0.1.0
  slh36064.dll                                        : 1.0.2.0
  slInit64.dll                                        : 1.1.1.0
  sltshd64.dll                                        : 1.1.0.0
  sluapo64.dll                                        : 1.2.6.0
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5766
  RtkUpd.exe                                          : 2.7.1.1
  RHCoInst.dll                                        : 1.0.3.2
  RHDMIExt.dll                                        : 6.0.6000.66
  RtkHDMI.dll                                         : 11.0.6000.85

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5766
  RtkUpd64.exe                                        : 2.7.1.1
  RHCoInst64.dll                                      : 1.0.3.2
  RHDMEx64.dll                                        : 6.0.6000.66
  RtkHDM64.dll                                        : 11.0.6000.85

  XP/2K x86:
  RtkHDMI.sys                                         : 5.10.0.5766
  RtkUpd.exe                                          : 2.7.1.1

  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5766
  RtkUpd64.exe                                        : 2.7.1.1

  Driver Setup Program                                : 2.69
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013

//=================
Driver Package R2.13
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC665, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272, ALC273, ALC887
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC665, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272, ALC273, ALC887
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5767
  RTKHDAUD.sys                                        : 5.10.0.5767
  MicCal.exe                                          : 1.1.2.0
  RTHDCPL.exe                                         : 2.2.5.8
  RtkAudioService64.exe                               : 1.0.0.17
  RtkAudioService.exe                                 : 1.0.0.16
  RTLCPL.exe                                          : 1.0.1.66
  RtlUpd64.exe                                        : 2.7.1.1
  RtlUpd.exe                                          : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.32
  vncutil64.exe                                       : 1.0.0.23
  vncutil.exe                                         : 1.0.0.23
  Alcmtr.exe                                          : 1.6.0.3
  AlcWzrd.exe                                         : 1.1.0.37
  AMBFilt64.sys                                       : 5.10.0.4240
  AMBFilt.sys                                         : 5.10.0.4240
  Monfilt64.sys                                       : 5.10.0.4115
  Monfilt.sys                                         : 5.10.0.4112
  RTSndMgr.cpl                                        : 1.0.1.0
  ALSndMgr.cpl                                        : 1.0.0.11
  RCoInst64XP.dll                                     : 1.0.4.3
  RTCOMDLL.dll                                        : 1.0.0.97
  RtkCoInstXP.dll                                     : 1.0.4.3
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5767
  AERTSrv.exe                                         : 1.0.32.8
  RtHDVCpl.exe                                        : 1.0.0.288
  RtkAudioService.exe                                 : 1.0.0.17
  RtlUpd.exe                                          : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.2
  vncutil.exe                                         : 1.0.0.23
  RTSndMgr.cpl                                        : 1.0.0.13
  AERTACap.dll                                        : 2.0.32.1
  AERTARen.dll                                        : 1.0.32.7
  CTAPO32.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO.dll                                           : 0.0.12.1
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.2.2.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  ppchain.dll                                         : 1.0.0.70
  RTCOMDLL.dll                                        : 2.0.0.105
  RtkAPO.dll                                          : 11.0.6000.85
  RtkApoApi.dll                                       : 1.0.0.9
  RtkCfg.dll                                          : 1.0.0.1
  RtkCoInst.dll                                       : 1.0.4.3
  RtkPgExt.dll                                        : 6.0.6000.66
  RtlCPAPI.dll                                        : 1.0.2.1
  slcshp32.dll                                        : 1.0.3.0
  slgeq32.dll                                         : 1.0.1.0
  slh36032.dll                                        : 1.0.2.0
  slInit32.dll                                        : 1.1.1.0
  sltshd32.dll                                        : 1.1.0.0
  sluapo32.dll                                        : 1.2.6.0
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5767
  AERTSr64.exe                                        : 1.0.64.8
  RAVCpl64.exe                                        : 1.0.0.288
  RtkAudioService64.exe                               : 1.0.0.17
  RtlUpd64.exe                                        : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.2
  vncutil64.exe                                       : 1.0.0.23
  GWfilt64.sys                                        : 6.10.0.3
  RTSnMg64.cpl                                        : 1.0.0.13
  AERTAC64.dll                                        : 2.0.64.1
  AERTAR64.dll                                        : 1.0.64.7
  CTAPO32.dll                                         : 1.0.0.530
  CTAPO64.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO64.dll                                         : 0.0.12.1
  MaxxAudioAPO20.dll                                  : 2.2.2.0
  ppchain.dll                                         : 1.0.0.70
  RCoInst64.dll                                       : 1.0.4.3
  RtCOM64.dll                                         : 2.0.0.105
  RTCOMDLL.dll                                        : 2.0.0.105
  RtkApi64.dll                                        : 1.0.0.9
  RtkAPO64.dll                                        : 11.0.6000.85
  RtkCfg.dll                                          : 1.0.0.1
  RtkCfg64.dll                                        : 1.0.0.1
  RtlCPAPI.dll                                        : 1.0.2.1
  RtlCPAPI64.dll                                      : 1.0.2.1
  RtPgEx64.dll                                        : 6.0.6000.66
  slcshp64.dll                                        : 1.0.3.0
  slgeq64.dll                                         : 1.0.1.0
  slh36064.dll                                        : 1.0.2.0
  slInit64.dll                                        : 1.1.1.0
  sltshd64.dll                                        : 1.1.0.0
  sluapo64.dll                                        : 1.2.6.0
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5766
  RtkUpd.exe                                          : 2.7.1.1
  RHCoInst.dll                                        : 1.0.3.2
  RHDMIExt.dll                                        : 6.0.6000.66
  RtkHDMI.dll                                         : 11.0.6000.85

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5766
  RtkUpd64.exe                                        : 2.7.1.1
  RHCoInst64.dll                                      : 1.0.3.2
  RHDMEx64.dll                                        : 6.0.6000.66
  RtkHDM64.dll                                        : 11.0.6000.85

  XP/2K x86:
  RtkHDMI.sys                                         : 5.10.0.5766
  RtkUpd.exe                                          : 2.7.1.1

  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5766
  RtkUpd64.exe                                        : 2.7.1.1

  Driver Setup Program                                : 2.69
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013

//=================
Driver Package R2.12
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC665, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272, ALC273, ALC887
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC665, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272, ALC273, ALC887
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.    
            2. Support encryption feature for ALC670.

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5764
  RTKHDAUD.sys                                        : 5.10.0.5764
  Alcmtr.exe                                          : 1.6.0.3
  AlcWzrd.exe                                         : 1.1.0.37
  MicCal.exe                                          : 1.1.2.0
  RTHDCPL.exe                                         : 2.2.5.6
  RtkAudioService64.exe                               : 1.0.0.17
  RtkAudioService.exe                                 : 1.0.0.16
  RTLCPL.exe                                          : 1.0.1.66
  RtlUpd64.exe                                        : 2.7.1.1
  RtlUpd.exe                                          : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.32
  vncutil64.exe                                       : 1.0.0.23
  vncutil.exe                                         : 1.0.0.23
  AMBFilt64.sys                                       : 5.10.0.4240
  AMBFilt.sys                                         : 5.10.0.4240
  Monfilt64.sys                                       : 5.10.0.4115
  Monfilt.sys                                         : 5.10.0.4112
  ALSndMgr.cpl                                        : 1.0.0.11
  RTSndMgr.cpl                                        : 1.0.1.0
  RCoInst64XP.dll                                     : 1.0.4.3
  RTCOMDLL.dll                                        : 1.0.0.97
  RtkCoInstXP.dll                                     : 1.0.4.3
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5764
  AERTSrv.exe                                         : 1.0.32.8
  RtHDVCpl.exe                                        : 1.0.0.286
  RtkAudioService.exe                                 : 1.0.0.17
  RtlUpd.exe                                          : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.2
  vncutil.exe                                         : 1.0.0.23
  RTSndMgr.cpl                                        : 1.0.0.13
  AERTACap.dll                                        : 2.0.32.1
  AERTARen.dll                                        : 1.0.32.7
  CTAPO32.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO.dll                                           : 0.0.12.1
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.2.2.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  ppchain.dll                                         : 1.0.0.70
  RTCOMDLL.dll                                        : 2.0.0.105
  RtkAPO.dll                                          : 11.0.6000.85
  RtkApoApi.dll                                       : 1.0.0.9
  RtkCfg.dll                                          : 1.0.0.1
  RtkCoInst.dll                                       : 1.0.4.3
  RtkPgExt.dll                                        : 6.0.6000.66
  RtlCPAPI.dll                                        : 1.0.2.1
  slcshp32.dll                                        : 1.0.3.0
  slgeq32.dll                                         : 1.0.1.0
  slh36032.dll                                        : 1.0.2.0
  slInit32.dll                                        : 1.1.1.0
  sltshd32.dll                                        : 1.1.0.0
  sluapo32.dll                                        : 1.2.6.0
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5764
  AERTSr64.exe                                        : 1.0.64.8
  RAVCpl64.exe                                        : 1.0.0.286
  RtkAudioService64.exe                               : 1.0.0.17
  RtlUpd64.exe                                        : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.2
  vncutil64.exe                                       : 1.0.0.23
  GWfilt64.sys                                        : 6.10.0.3
  RTSnMg64.cpl                                        : 1.0.0.13
  AERTAC64.dll                                        : 2.0.64.1
  AERTAR64.dll                                        : 1.0.64.7
  CTAPO32.dll                                         : 1.0.0.530
  CTAPO64.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO64.dll                                         : 0.0.12.1
  MaxxAudioAPO20.dll                                  : 2.2.2.0
  ppchain.dll                                         : 1.0.0.70
  RCoInst64.dll                                       : 1.0.4.3
  RtCOM64.dll                                         : 2.0.0.105
  RTCOMDLL.dll                                        : 2.0.0.105
  RtkApi64.dll                                        : 1.0.0.9
  RtkAPO64.dll                                        : 11.0.6000.85
  RtkCfg.dll                                          : 1.0.0.1
  RtkCfg64.dll                                        : 1.0.0.1
  RtlCPAPI.dll                                        : 1.0.2.1
  RtlCPAPI64.dll                                      : 1.0.2.1
  RtPgEx64.dll                                        : 6.0.6000.66
  slcshp64.dll                                        : 1.0.3.0
  slgeq64.dll                                         : 1.0.1.0
  slh36064.dll                                        : 1.0.2.0
  slInit64.dll                                        : 1.1.1.0
  sltshd64.dll                                        : 1.1.0.0
  sluapo64.dll                                        : 1.2.6.0
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5735
  RtkUpd.exe                                          : 2.7.1.1
  RHCoInst.dll                                        : 1.0.3.2
  RHDMIExt.dll                                        : 6.0.6000.64
  RtkHDMI.dll                                         : 11.0.6000.80


  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5735
  RtkUpd64.exe                                        : 2.7.1.1
  RHCoInst64.dll                                      : 1.0.3.2
  RHDMEx64.dll                                        : 6.0.6000.64
  RtkHDM64.dll                                        : 11.0.6000.80

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5735
  RtkUpd.exe                                          : 2.7.1.1
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5735
  RtkUpd64.exe                                        : 2.7.1.1

  Driver Setup Program                                : 2.69
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013

//=================
Driver Package R2.11
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC665, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272, ALC273, ALC887
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC665, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272, ALC273, ALC887
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.    
            2. Add DisplayVersion registry key in INF files.        

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5755
  RTKHDAUD.sys                                        : 5.10.0.5755
  Alcmtr.exe                                          : 1.6.0.3
  AlcWzrd.exe                                         : 1.1.0.37
  MicCal.exe                                          : 1.1.2.0
  RTHDCPL.exe                                         : 2.2.5.5
  RtkAudioService64.exe                               : 1.0.0.17
  RtkAudioService.exe                                 : 1.0.0.16
  RTLCPL.exe                                          : 1.0.1.66
  RtlUpd64.exe                                        : 2.7.1.1
  RtlUpd.exe                                          : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.32
  vncutil64.exe                                       : 1.0.0.22
  vncutil.exe                                         : 1.0.0.22
  AMBFilt64.sys                                       : 5.10.0.4240
  AMBFilt.sys                                         : 5.10.0.4240
  Monfilt64.sys                                       : 5.10.0.4115
  Monfilt.sys                                         : 5.10.0.4112
  ALSndMgr.cpl                                        : 1.0.0.11
  RTSndMgr.cpl                                        : 1.0.1.0
  RCoInst64XP.dll                                     : 1.0.4.1
  RTCOMDLL.dll                                        : 1.0.0.97
  RtkCoInstXP.dll                                     : 1.0.4.1
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5755
  AERTSrv.exe                                         : 1.0.32.8
  RtHDVCpl.exe                                        : 1.0.0.281
  RtkAudioService.exe                                 : 1.0.0.17
  RtlUpd.exe                                          : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.2
  vncutil.exe                                         : 1.0.0.23
  RTSndMgr.cpl                                        : 1.0.0.13
  AERTACap.dll                                        : 2.0.32.1
  AERTARen.dll                                        : 1.0.32.7
  CTAPO32.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO.dll                                           : 0.0.12.1
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.2.2.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  ppchain.dll                                         : 1.0.0.70
  RTCOMDLL.dll                                        : 2.0.0.103
  RtkAPO.dll                                          : 11.0.6000.81
  RtkApoApi.dll                                       : 1.0.0.9
  RtkCfg.dll                                          : 1.0.0.1
  RtkCoInst.dll                                       : 1.0.4.1
  RtkPgExt.dll                                        : 6.0.6000.65
  RtlCPAPI.dll                                        : 1.0.2.1
  slcshp32.dll                                        : 1.0.3.0
  slgeq32.dll                                         : 1.0.1.0
  slh36032.dll                                        : 1.0.2.0
  slInit32.dll                                        : 1.1.1.0
  sltshd32.dll                                        : 1.1.0.0
  sluapo32.dll                                        : 1.2.6.0
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5755
  AERTSr64.exe                                        : 1.0.64.8
  RAVCpl64.exe                                        : 1.0.0.281
  RtkAudioService64.exe                               : 1.0.0.17
  RtlUpd64.exe                                        : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.2
  vncutil64.exe                                       : 1.0.0.23
  GWfilt64.sys                                        : 6.10.0.3
  RTSnMg64.cpl                                        : 1.0.0.13
  AERTAC64.dll                                        : 2.0.64.1
  AERTAR64.dll                                        : 1.0.64.7
  CTAPO32.dll                                         : 1.0.0.530
  CTAPO64.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO64.dll                                         : 0.0.12.1
  MaxxAudioAPO20.dll                                  : 2.2.2.0
  ppchain.dll                                         : 1.0.0.70
  RCoInst64.dll                                       : 1.0.4.1
  RtCOM64.dll                                         : 2.0.0.103
  RTCOMDLL.dll                                        : 2.0.0.103
  RtkApi64.dll                                        : 1.0.0.9
  RtkAPO64.dll                                        : 11.0.6000.81
  RtkCfg.dll                                          : 1.0.0.1
  RtkCfg64.dll                                        : 1.0.0.1
  RtlCPAPI.dll                                        : 1.0.2.1
  RtlCPAPI64.dll                                      : 1.0.2.1
  RtPgEx64.dll                                        : 6.0.6000.65
  slcshp64.dll                                        : 1.0.3.0
  slgeq64.dll                                         : 1.0.1.0
  slh36064.dll                                        : 1.0.2.0
  slInit64.dll                                        : 1.1.1.0
  sltshd64.dll                                        : 1.1.0.0
  sluapo64.dll                                        : 1.2.6.0
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5735
  RtkUpd.exe                                          : 2.7.1.1
  RHCoInst.dll                                        : 1.0.3.2
  RHDMIExt.dll                                        : 6.0.6000.64
  RtkHDMI.dll                                         : 11.0.6000.80


  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5735
  RtkUpd64.exe                                        : 2.7.1.1
  RHCoInst64.dll                                      : 1.0.3.2
  RHDMEx64.dll                                        : 6.0.6000.64
  RtkHDM64.dll                                        : 11.0.6000.80

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5735
  RtkUpd.exe                                          : 2.7.1.1
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5735
  RtkUpd64.exe                                        : 2.7.1.1

  Driver Setup Program                                : 2.69
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013

//=================
Driver Package R2.10
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC665, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272, ALC273, ALC887
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC665, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272, ALC273, ALC887
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.    
            2. Support ALC665.        
        

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5745
  RTKHDAUD.sys                                        : 5.10.0.5745
  MicCal.exe                                          : 1.1.2.0
  RTHDCPL.exe                                         : 2.2.5.2
  RtkAudioService64.exe                               : 1.0.0.17
  RtkAudioService.exe                                 : 1.0.0.16
  RTLCPL.exe                                          : 1.0.1.66
  RtlUpd64.exe                                        : 2.7.1.1
  RtlUpd.exe                                          : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.32
  vncutil64.exe                                       : 1.0.0.22
  vncutil.exe                                         : 1.0.0.22
  Alcmtr.exe                                          : 1.6.0.3
  AlcWzrd.exe                                         : 1.1.0.37
  AMBFilt64.sys                                       : 5.10.0.4240
  AMBFilt.sys                                         : 5.10.0.4240
  Monfilt64.sys                                       : 5.10.0.4115
  Monfilt.sys                                         : 5.10.0.4112
  RTSndMgr.cpl                                        : 1.0.1.0
  ALSndMgr.cpl                                        : 1.0.0.11
  RCoInst64XP.dll                                     : 1.0.4.1
  RTCOMDLL.dll                                        : 1.0.0.97
  RtkCoInstXP.dll                                     : 1.0.4.1
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5745
  AERTSrv.exe                                         : 1.0.32.8
  RtHDVCpl.exe                                        : 1.0.0.273
  RtkAudioService.exe                                 : 1.0.0.17
  RtlUpd.exe                                          : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.2
  vncutil.exe                                         : 1.0.0.22
  RTSndMgr.cpl                                        : 1.0.0.13
  AERTACap.dll                                        : 2.0.32.1
  AERTARen.dll                                        : 1.0.32.7
  CTAPO32.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO.dll                                           : 0.0.12.1
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.2.2.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  ppchain.dll                                         : 1.0.0.70
  RCoInst64.dll                                       : 1.0.4.0
  RTCOMDLL.dll                                        : 2.0.0.103
  RtkAPO.dll                                          : 11.0.6000.81
  RtkApoApi.dll                                       : 1.0.0.9
  RtkCfg.dll                                          : 1.0.0.1
  RtkCoInst.dll                                       : 1.0.4.1
  RtkPgExt.dll                                        : 6.0.6000.65
  RtlCPAPI.dll                                        : 1.0.2.1
  slcshp32.dll                                        : 1.0.3.0
  slgeq32.dll                                         : 1.0.1.0
  slh36032.dll                                        : 1.0.2.0
  slInit32.dll                                        : 1.1.1.0
  sltshd32.dll                                        : 1.1.0.0
  sluapo32.dll                                        : 1.2.6.0
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5745
  AERTSr64.exe                                        : 1.0.64.8
  RAVCpl64.exe                                        : 1.0.0.273
  RtkAudioService64.exe                               : 1.0.0.17
  RtlUpd64.exe                                        : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.2
  vncutil64.exe                                       : 1.0.0.22
  GWfilt64.sys                                        : 6.10.0.3
  RTSnMg64.cpl                                        : 1.0.0.13
  AERTAC64.dll                                        : 2.0.64.1
  AERTAR64.dll                                        : 1.0.64.7
  CTAPO32.dll                                         : 1.0.0.530
  CTAPO64.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO64.dll                                         : 0.0.12.1
  MaxxAudioAPO20.dll                                  : 2.2.2.0
  ppchain.dll                                         : 1.0.0.70
  RCoInst64.dll                                       : 1.0.4.1
  RtCOM64.dll                                         : 2.0.0.103
  RTCOMDLL.dll                                        : 2.0.0.103
  RtkApi64.dll                                        : 1.0.0.9
  RtkAPO64.dll                                        : 11.0.6000.81
  RtkCfg.dll                                          : 1.0.0.1
  RtkCfg64.dll                                        : 1.0.0.1
  RtkCoInst.dll                                       : 1.0.4.0
  RtlCPAPI.dll                                        : 1.0.2.1
  RtlCPAPI64.dll                                      : 1.0.2.1
  RtPgEx64.dll                                        : 6.0.6000.65
  slcshp64.dll                                        : 1.0.3.0
  slgeq64.dll                                         : 1.0.1.0
  slh36064.dll                                        : 1.0.2.0
  slInit64.dll                                        : 1.1.1.0
  sltshd64.dll                                        : 1.1.0.0
  sluapo64.dll                                        : 1.2.6.0
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5735
  RtkUpd.exe                                          : 2.7.1.1
  RHCoInst.dll                                        : 1.0.3.2
  RHDMIExt.dll                                        : 6.0.6000.64
  RtkHDMI.dll                                         : 11.0.6000.80


  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5735
  RtkUpd64.exe                                        : 2.7.1.1
  RHCoInst64.dll                                      : 1.0.3.2
  RHDMEx64.dll                                        : 6.0.6000.64
  RtkHDM64.dll                                        : 11.0.6000.80

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5735
  RtkUpd.exe                                          : 2.7.1.1
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5735
  RtkUpd64.exe                                        : 2.7.1.1

  Driver Setup Program                                : 2.69
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013

//=================
Driver Package R2.09
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272, ALC273, ALC887
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272, ALC273, ALC887
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.            
        

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5735
  RTKHDAUD.sys                                        : 5.10.0.5735
  Alcmtr.exe                                          : 1.6.0.3
  AlcWzrd.exe                                         : 1.1.0.37
  MicCal.exe                                          : 1.1.2.0
  RTHDCPL.exe                                         : 2.2.5.1
  RtkAudioService.exe                                 : 1.0.0.16
  RtkAudioService64.exe                               : 1.0.0.17
  RTLCPL.exe                                          : 1.0.1.66
  RtlUpd.exe                                          : 2.7.1.1
  RtlUpd64.exe                                        : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.32
  vncutil.exe                                         : 1.0.0.22
  vncutil64.exe                                       : 1.0.0.22
  AMBFilt.sys                                         : 5.10.0.4240
  AMBFilt64.sys                                       : 5.10.0.4240
  Monfilt.sys                                         : 5.10.0.4112
  Monfilt64.sys                                       : 5.10.0.4115
  ALSndMgr.cpl                                        : 1.0.0.11
  RTSndMgr.cpl                                        : 1.0.1.0
  RCoInst64XP.dll                                     : 1.0.3.9
  RTCOMDLL.dll                                        : 1.0.0.97
  RtkCoInstXP.dll                                     : 1.0.3.9
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5735
  AERTSrv.exe                                         : 1.0.32.8
  RtHDVCpl.exe                                        : 1.0.0.264
  RtkAudioService.exe                                 : 1.0.0.17
  RtlUpd.exe                                          : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.22
  RTSndMgr.cpl                                        : 1.0.0.13
  AERTACap.dll                                        : 2.0.32.1
  AERTARen.dll                                        : 1.0.32.7
  CTAPO32.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO.dll                                           : 0.0.12.1
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.2.2.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  ppchain.dll                                         : 1.0.0.70
  RTCOMDLL.dll                                        : 2.0.0.100
  RtkAPO.dll                                          : 11.0.6000.80
  RtkApoApi.dll                                       : 1.0.0.8
  RtkCoInst.dll                                       : 1.0.3.9
  RtkPgExt.dll                                        : 6.0.6000.64
  RtlCPAPI.dll                                        : 1.0.1.9
  slcshp32.dll                                        : 1.0.3.0
  slgeq32.dll                                         : 1.0.1.0
  slh36032.dll                                        : 1.0.2.0
  slInit32.dll                                        : 1.1.1.0
  sltshd32.dll                                        : 1.1.0.0
  sluapo32.dll                                        : 1.2.6.0
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5735
  AERTSr64.exe                                        : 1.0.64.8
  RAVCpl64.exe                                        : 1.0.0.264
  RtkAudioService64.exe                               : 1.0.0.17
  RtlUpd64.exe                                        : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.1
  vncutil64.exe                                       : 1.0.0.22
  GWfilt64.sys                                        : 6.10.0.3
  RTSnMg64.cpl                                        : 1.0.0.13
  AERTAC64.dll                                        : 2.0.64.1
  AERTAR64.dll                                        : 1.0.64.7
  CTAPO32.dll                                         : 1.0.0.530
  CTAPO64.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO64.dll                                         : 0.0.12.1
  MaxxAudioAPO20.dll                                  : 2.2.2.0
  ppchain.dll                                         : 1.0.0.70
  RCoInst64.dll                                       : 1.0.3.9
  RtCOM64.dll                                         : 2.0.0.100
  RTCOMDLL.dll                                        : 2.0.0.100
  RtkApi64.dll                                        : 1.0.0.8
  RtkAPO64.dll                                        : 11.0.6000.80
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.64
  slcshp64.dll                                        : 1.0.3.0
  slgeq64.dll                                         : 1.0.1.0
  slh36064.dll                                        : 1.0.2.0
  slInit64.dll                                        : 1.1.1.0
  sltshd64.dll                                        : 1.1.0.0
  sluapo64.dll                                        : 1.2.6.0
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5735
  RtkUpd.exe                                          : 2.7.1.1
  RHCoInst.dll                                        : 1.0.3.2
  RHDMIExt.dll                                        : 6.0.6000.64
  RtkHDMI.dll                                         : 11.0.6000.80


  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5735
  RtkUpd64.exe                                        : 2.7.1.1
  RHCoInst64.dll                                      : 1.0.3.2
  RHDMEx64.dll                                        : 6.0.6000.64
  RtkHDM64.dll                                        : 11.0.6000.80

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5735
  RtkUpd.exe                                          : 2.7.1.1
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5735
  RtkUpd64.exe                                        : 2.7.1.1

  Driver Setup Program                                : 2.67
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013

//=================
Driver Package R2.08
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272, ALC273, ALC887
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272, ALC273, ALC887
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
            2. Support Andrea microphone effect mixer type GUI.
        2.) Package:
            1. Change setup program install location to meet the requirements of OEM Ready Certification Tool 1.1.0.1101


     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5730
  RTKHDAUD.sys                                        : 5.10.0.5730
  MicCal.exe                                          : 1.1.2.0
  RTHDCPL.exe                                         : 2.2.4.9
  RtkAudioService64.exe                               : 1.0.0.17
  RtkAudioService.exe                                 : 1.0.0.16
  RTLCPL.exe                                          : 1.0.1.66
  RtlUpd64.exe                                        : 2.7.1.1
  RtlUpd.exe                                          : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.32
  vncutil64.exe                                       : 1.0.0.22
  vncutil.exe                                         : 1.0.0.22
  Alcmtr.exe                                          : 1.6.0.3
  AlcWzrd.exe                                         : 1.1.0.37
  Monfilt64.sys                                       : 5.10.0.4115
  Monfilt.sys                                         : 5.10.0.4112
  AMBFilt64.sys                                       : 5.10.0.4240
  AMBFilt.sys                                         : 5.10.0.4240
  RTSndMgr.cpl                                        : 1.0.1.0
  ALSndMgr.cpl                                        : 1.0.0.11
  RCoInst64XP.dll                                     : 1.0.3.8
  RTCOMDLL.dll                                        : 1.0.0.97
  RtkCoInstXP.dll                                     : 1.0.3.8
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5730
  AERTSrv.exe                                         : 1.0.32.8
  RtHDVCpl.exe                                        : 1.0.0.257
  RtkAudioService.exe                                 : 1.0.0.17
  RtlUpd.exe                                          : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.22
  RTSndMgr.cpl                                        : 1.0.0.10
  AERTACap.dll                                        : 2.0.32.1
  AERTARen.dll                                        : 1.0.32.7
  CTAPO32.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO.dll                                           : 0.0.12.1
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.0.13.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  ppchain.dll                                         : 1.0.0.70
  RTCOMDLL.dll                                        : 2.0.0.100
  RtkAPO.dll                                          : 11.0.6000.79
  RtkApoApi.dll                                       : 1.0.0.8
  RtkCoInst.dll                                       : 1.0.3.8
  RtkPgExt.dll                                        : 6.0.6000.64
  RtlCPAPI.dll                                        : 1.0.1.9
  slcshp32.dll                                        : 1.0.3.0
  slgeq32.dll                                         : 1.0.1.0
  slh36032.dll                                        : 1.0.2.0
  slInit32.dll                                        : 1.1.1.0
  sltshd32.dll                                        : 1.1.0.0
  sluapo32.dll                                        : 1.2.6.0
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5730
  AERTSr64.exe                                        : 1.0.64.8
  RAVCpl64.exe                                        : 1.0.0.257
  RtkAudioService64.exe                               : 1.0.0.17
  RtlUpd64.exe                                        : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.1
  vncutil64.exe                                       : 1.0.0.22
  GWfilt64.sys                                        : 6.10.0.3
  RTSnMg64.cpl                                        : 1.0.0.10
  AERTAC64.dll                                        : 2.0.64.1
  AERTAR64.dll                                        : 1.0.64.7
  CTAPO32.dll                                         : 1.0.0.530
  CTAPO64.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO64.dll                                         : 0.0.12.1
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  ppchain.dll                                         : 1.0.0.70
  RCoInst64.dll                                       : 1.0.3.8
  RtCOM64.dll                                         : 2.0.0.100
  RTCOMDLL.dll                                        : 2.0.0.100
  RtkApi64.dll                                        : 1.0.0.8
  RtkAPO64.dll                                        : 11.0.6000.79
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.64
  slcshp64.dll                                        : 1.0.3.0
  slgeq64.dll                                         : 1.0.1.0
  slh36064.dll                                        : 1.0.2.0
  slInit64.dll                                        : 1.1.1.0
  sltshd64.dll                                        : 1.1.0.0
  sluapo64.dll                                        : 1.2.6.0
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5692
  RtkUpd.exe                                          : 2.7.1.0
  RHCoInst.dll                                        : 1.0.3.2
  RHDMIExt.dll                                        : 6.0.6000.54
  RtkHDMI.dll                                         : 11.0.6000.72

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5692
  RtkUpd64.exe                                        : 2.7.1.0
  RHCoInst64.dll                                      : 1.0.3.2
  RHDMEx64.dll                                        : 6.0.6000.54
  RtkHDM64.dll                                        : 11.0.6000.72

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5692
  RtkUpd.exe                                          : 2.7.1.0
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5692
  RtkUpd64.exe                                        : 2.7.1.0

  Driver Setup Program                                : 2.67
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R2.07
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272, ALC273, ALC887
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272, ALC273, ALC887
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
    
     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5717
  RTKHDAUD.sys                                        : 5.10.0.5717
  Alcmtr.exe                                          : 1.6.0.3
  AlcWzrd.exe                                         : 1.1.0.37
  MicCal.exe                                          : 1.1.2.0
  RTHDCPL.exe                                         : 2.2.4.8
  RTLCPL.exe                                          : 1.0.1.66
  RtlUpd.exe                                          : 2.7.1.1
  RtlUpd64.exe                                        : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.32
  AMBFilt.sys                                         : 5.10.0.4240
  AMBFilt64.sys                                       : 5.10.0.4240
  Monfilt.sys                                         : 5.10.0.4112
  Monfilt64.sys                                       : 5.10.0.4115
  ALSndMgr.cpl                                        : 1.0.0.11
  RTSndMgr.cpl                                        : 1.0.1.0
  RTCOMDLL.dll                                        : 1.0.0.97
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5717
  AERTSrv.exe                                         : 1.0.32.7
  RtHDVCpl.exe                                        : 1.0.0.251
  RtkAudioService.exe                                 : 1.0.0.17
  RtlUpd.exe                                          : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.22
  RTSndMgr.cpl                                        : 1.0.0.10
  AERTACap.dll                                        : 1.0.32.7
  AERTARen.dll                                        : 1.0.32.3
  CTAPO32.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO.dll                                           : 40.59.0.0
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.0.13.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  ppchain.dll                                         : 1.0.0.70
  RTCOMDLL.dll                                        : 2.0.0.100
  RtkAPO.dll                                          : 11.0.6000.78
  RtkApoApi.dll                                       : 1.0.0.6
  RtkCoInst.dll                                       : 1.0.3.7
  RtkPgExt.dll                                        : 6.0.6000.61
  RtlCPAPI.dll                                        : 1.0.1.9
  slcshp32.dll                                        : 1.0.3.0
  slgeq32.dll                                         : 1.0.1.0
  slh36032.dll                                        : 1.0.2.0
  slInit32.dll                                        : 1.1.1.0
  sltshd32.dll                                        : 1.1.0.0
  sluapo32.dll                                        : 1.2.6.0
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5717
  AERTSr64.exe                                        : 1.0.64.7
  RAVCpl64.exe                                        : 1.0.0.251
  RtkAudioService.exe                                 : 1.0.0.17
  RtlUpd64.exe                                        : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.22
  GWfilt64.sys                                        : 6.10.0.3
  RTSnMg64.cpl                                        : 1.0.0.10
  AERTAC64.dll                                        : 1.0.64.7
  AERTAR64.dll                                        : 1.0.64.3
  CTAPO32.dll                                         : 1.0.0.530
  CTAPO64.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO64.dll                                         : 40.59.0.0
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  ppchain.dll                                         : 1.0.0.70
  RCoInst64.dll                                       : 1.0.3.7
  RtCOM64.dll                                         : 2.0.0.100
  RTCOMDLL.dll                                        : 2.0.0.100
  RtkApi64.dll                                        : 1.0.0.6
  RtkAPO64.dll                                        : 11.0.6000.78
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.61
  slcshp64.dll                                        : 1.0.3.0
  slgeq64.dll                                         : 1.0.1.0
  slh36064.dll                                        : 1.0.2.0
  slInit64.dll                                        : 1.1.1.0
  sltshd64.dll                                        : 1.1.0.0
  sluapo64.dll                                        : 1.2.6.0
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5692
  RtkUpd.exe                                          : 2.7.1.0
  RHCoInst.dll                                        : 1.0.3.2
  RHDMIExt.dll                                        : 6.0.6000.54
  RtkHDMI.dll                                         : 11.0.6000.72

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5692
  RtkUpd64.exe                                        : 2.7.1.0
  RHCoInst64.dll                                      : 1.0.3.2
  RHDMEx64.dll                                        : 6.0.6000.54
  RtkHDM64.dll                                        : 11.0.6000.72

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5692
  RtkUpd.exe                                          : 2.7.1.0
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5692
  RtkUpd64.exe                                        : 2.7.1.0

  Driver Setup Program                                : 2.64
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R2.06
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272, ALC273, ALC887
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272, ALC273, ALC887
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
    
     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5713
  RTKHDAUD.sys                                        : 5.10.0.5713
  Alcmtr.exe                                          : 1.6.0.3
  AlcWzrd.exe                                         : 1.1.0.37
  MicCal.exe                                          : 1.1.2.0
  RTHDCPL.exe                                         : 2.2.4.6
  RTLCPL.exe                                          : 1.0.1.66
  RtlUpd64.exe                                        : 2.7.1.1
  RtlUpd.exe                                          : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.32
  AMBFilt64.sys                                       : 5.10.0.4240
  AMBFilt.sys                                         : 5.10.0.4240
  Monfilt64.sys                                       : 5.10.0.4115
  Monfilt.sys                                         : 5.10.0.4112
  ALSndMgr.cpl                                        : 1.0.0.11
  RTSndMgr.cpl                                        : 1.0.1.0
  RTCOMDLL.dll                                        : 1.0.0.97
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5713
  AERTSrv.exe                                         : 1.0.32.7
  RtHDVCpl.exe                                        : 1.0.0.248
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd.exe                                          : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.22
  RTSndMgr.cpl                                        : 1.0.0.10
  AERTACap.dll                                        : 1.0.32.7
  AERTARen.dll                                        : 1.0.32.3
  CTAPO32.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO.dll                                           : 40.59.0.0
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.0.13.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  ppchain.dll                                         : 1.0.0.70
  RTCOMDLL.dll                                        : 2.0.0.100
  RtkAPO.dll                                          : 11.0.6000.77
  RtkApoApi.dll                                       : 1.0.0.6
  RtkCoInst.dll                                       : 1.0.3.6
  RtkPgExt.dll                                        : 6.0.6000.61
  RtlCPAPI.dll                                        : 1.0.1.9
  slcshp32.dll                                        : 1.0.3.0
  slgeq32.dll                                         : 1.0.1.0
  slh36032.dll                                        : 1.0.2.0
  slInit32.dll                                        : 1.1.1.0
  sltshd32.dll                                        : 1.1.0.0
  sluapo32.dll                                        : 1.2.6.0
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5713
  AERTSr64.exe                                        : 1.0.64.7
  RAVCpl64.exe                                        : 1.0.0.248
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd64.exe                                        : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.22
  GWfilt64.sys                                        : 6.10.0.3
  RTSnMg64.cpl                                        : 1.0.0.10
  AERTAC64.dll                                        : 1.0.64.7
  AERTAR64.dll                                        : 1.0.64.3
  CTAPO32.dll                                         : 1.0.0.530
  CTAPO64.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO64.dll                                         : 40.59.0.0
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  ppchain.dll                                         : 1.0.0.70
  RCoInst64.dll                                       : 1.0.3.6
  RtCOM64.dll                                         : 2.0.0.100
  RTCOMDLL.dll                                        : 2.0.0.100
  RtkApi64.dll                                        : 1.0.0.6
  RtkAPO64.dll                                        : 11.0.6000.77
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.61
  slcshp64.dll                                        : 1.0.3.0
  slgeq64.dll                                         : 1.0.1.0
  slh36064.dll                                        : 1.0.2.0
  slInit64.dll                                        : 1.1.1.0
  sltshd64.dll                                        : 1.1.0.0
  sluapo64.dll                                        : 1.2.6.0
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5692
  RtkUpd.exe                                          : 2.7.1.0
  RHCoInst.dll                                        : 1.0.3.2
  RHDMIExt.dll                                        : 6.0.6000.54
  RtkHDMI.dll                                         : 11.0.6000.72

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5692
  RtkUpd64.exe                                        : 2.7.1.0
  RHCoInst64.dll                                      : 1.0.3.2
  RHDMEx64.dll                                        : 6.0.6000.54
  RtkHDM64.dll                                        : 11.0.6000.72

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5692
  RtkUpd.exe                                          : 2.7.1.0
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5692
  RtkUpd64.exe                                        : 2.7.1.0

  Driver Setup Program                                : 2.64
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R2.05
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272, ALC273, ALC887
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272, ALC273, ALC887
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
            2. Meet Microsoft OEM Ready program requirements.
        2.) Package :
            1. Meet Microsoft OEM Ready program requirements.
            
     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5708
  RTKHDAUD.sys                                        : 5.10.0.5708
  MicCal.exe                                          : 1.1.1.9
  RTHDCPL.exe                                         : 2.2.4.5
  RTLCPL.exe                                          : 1.0.1.66
  RtlUpd64.exe                                        : 2.7.1.1
  RtlUpd.exe                                          : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.32
  Alcmtr.exe                                          : 1.6.0.3
  AlcWzrd.exe                                         : 1.1.0.37
  Monfilt64.sys                                       : 5.10.0.4115
  Monfilt.sys                                         : 5.10.0.4112
  AMBFilt64.sys                                       : 5.10.0.4240
  AMBFilt.sys                                         : 5.10.0.4240
  RTSndMgr.cpl                                        : 1.0.1.0
  ALSndMgr.cpl                                        : 1.0.0.11
  RTCOMDLL.dll                                        : 1.0.0.97
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5708
  AERTSrv.exe                                         : 1.0.32.7
  RtHDVCpl.exe                                        : 1.0.0.246
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd.exe                                          : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.21
  RTSndMgr.cpl                                        : 1.0.0.10
  AERTACap.dll                                        : 1.0.32.7
  AERTARen.dll                                        : 1.0.32.3
  CTAPO32.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO.dll                                           : 40.59.0.0
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.0.13.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  ppchain.dll                                         : 1.0.0.70
  RTCOMDLL.dll                                        : 2.0.0.100
  RtkAPO.dll                                          : 11.0.6000.76
  RtkApoApi.dll                                       : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.3.5
  RtkPgExt.dll                                        : 6.0.6000.60
  RtlCPAPI.dll                                        : 1.0.1.9
  slcshp32.dll                                        : 1.0.3.0
  slgeq32.dll                                         : 1.0.1.0
  slh36032.dll                                        : 1.0.2.0
  slInit32.dll                                        : 1.1.1.0
  sltshd32.dll                                        : 1.1.0.0
  sluapo32.dll                                        : 1.2.6.0
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5708
  AERTSr64.exe                                        : 1.0.64.7
  RAVCpl64.exe                                        : 1.0.0.246
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd64.exe                                        : 2.7.1.1
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.21
  GWfilt64.sys                                        : 6.10.0.3
  RTSnMg64.cpl                                        : 1.0.0.10
  AERTAC64.dll                                        : 1.0.64.7
  AERTAR64.dll                                        : 1.0.64.3
  CTAPO32.dll                                         : 1.0.0.530
  CTAPO64.dll                                         : 1.0.0.530
  ctppld.dll                                          : 1.0.0.530
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO64.dll                                         : 40.59.0.0
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  ppchain.dll                                         : 1.0.0.70
  RCoInst64.dll                                       : 1.0.3.5
  RtCOM64.dll                                         : 2.0.0.100
  RTCOMDLL.dll                                        : 2.0.0.100
  RtkApi64.dll                                        : 1.0.0.4
  RtkAPO64.dll                                        : 11.0.6000.76
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.60
  slcshp64.dll                                        : 1.0.3.0
  slgeq64.dll                                         : 1.0.1.0
  slh36064.dll                                        : 1.0.2.0
  slInit64.dll                                        : 1.1.1.0
  sltshd64.dll                                        : 1.1.0.0
  sluapo64.dll                                        : 1.2.6.0
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5692
  RtkUpd.exe                                          : 2.7.1.0
  RHCoInst.dll                                        : 1.0.3.2
  RHDMIExt.dll                                        : 6.0.6000.54
  RtkHDMI.dll                                         : 11.0.6000.72

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5692
  RtkUpd64.exe                                        : 2.7.1.0
  RHCoInst64.dll                                      : 1.0.3.2
  RHDMEx64.dll                                        : 6.0.6000.54
  RtkHDM64.dll                                        : 11.0.6000.72

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5692
  RtkUpd.exe                                          : 2.7.1.0
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5692
  RtkUpd64.exe                                        : 2.7.1.0

  Driver Setup Program                                : 2.64
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R2.04
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272, ALC273, ALC887
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272, ALC273, ALC887
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
            2. Support ALC887.
            
     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5700
  RTKHDAUD.sys                                        : 5.10.0.5700
  Alcmtr.exe                                          : 1.6.0.3
  AlcWzrd.exe                                         : 1.1.0.37
  MicCal.exe                                          : 1.1.1.8
  RTHDCPL.exe                                         : 2.2.4.0
  RTLCPL.exe                                          : 1.0.1.66
  RtlUpd64.exe                                        : 2.7.1.0
  RtlUpd.exe                                          : 2.7.1.0
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.32
  AMBFilt64.sys                                       : 5.10.0.4240
  AMBFilt.sys                                         : 5.10.0.4240
  Monfilt64.sys                                       : 5.10.0.4115
  Monfilt.sys                                         : 5.10.0.4112
  ALSndMgr.cpl                                        : 1.0.0.11
  RTSndMgr.cpl                                        : 1.0.1.0
  RTCOMDLL.dll                                        : 1.0.0.97
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5700
  AERTSrv.exe                                         : 1.0.32.7
  RtHDVCpl.exe                                        : 1.0.0.240
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd.exe                                          : 2.7.1.0
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.21
  RTSndMgr.cpl                                        : 1.0.0.9
  AERTACap.dll                                        : 1.0.32.7
  AERTARen.dll                                        : 1.0.32.3
  CTAPO32.dll                                         : 1.0.0.520
  ctppld.dll                                          : 1.0.0.510
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO.dll                                           : 40.59.0.0
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.0.13.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  ppchain.dll                                         : 1.0.0.70
  RTCOMDLL.dll                                        : 2.0.0.100
  RtkAPO.dll                                          : 11.0.6000.74
  RtkApoApi.dll                                       : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.3.2
  RtkPgExt.dll                                        : 6.0.6000.56
  RtlCPAPI.dll                                        : 1.0.1.9
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  GWfilt64.sys                                        : 6.10.0.3
  RTKVHD64.sys                                        : 6.0.1.5700
  AERTSr64.exe                                        : 1.0.64.7
  RAVCpl64.exe                                        : 1.0.0.240
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd64.exe                                        : 2.7.1.0
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.21
  RTSnMg64.cpl                                        : 1.0.0.9
  AERTAC64.dll                                        : 1.0.64.7
  AERTAR64.dll                                        : 1.0.64.3
  CTAPO32.dll                                         : 1.0.0.520
  CTAPO64.dll                                         : 1.0.0.520
  ctppld.dll                                          : 1.0.0.510
  DaisyWrp.dll                                        : 1.0.0.70
  FMAPO64.dll                                         : 40.59.0.0
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  ppchain.dll                                         : 1.0.0.70
  RCoInst64.dll                                       : 1.0.3.2
  RtCOM64.dll                                         : 2.0.0.100
  RTCOMDLL.dll                                        : 2.0.0.100
  RtkApi64.dll                                        : 1.0.0.4
  RtkAPO64.dll                                        : 11.0.6000.74
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.56
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5692
  RtkUpd.exe                                          : 2.7.1.0
  RHCoInst.dll                                        : 1.0.3.2
  RHDMIExt.dll                                        : 6.0.6000.54
  RtkHDMI.dll                                         : 11.0.6000.72

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5692
  RtkUpd64.exe                                        : 2.7.1.0
  RHCoInst64.dll                                      : 1.0.3.2
  RHDMEx64.dll                                        : 6.0.6000.54
  RtkHDM64.dll                                        : 11.0.6000.72

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5692
  RtkUpd.exe                                          : 2.7.1.0
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5692
  RtkUpd64.exe                                        : 2.7.1.0

  Driver Setup Program                                : 2.62
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R2.03
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272, ALC273
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272, ALC273
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
            
     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5694
  RTKHDAUD.sys                                        : 5.10.0.5694
  Alcmtr.exe                                          : 1.6.0.3
  AlcWzrd.exe                                         : 1.1.0.37
  MicCal.exe                                          : 1.1.1.8
  RTHDCPL.exe                                         : 2.2.3.8
  RTLCPL.exe                                          : 1.0.1.66
  RtlUpd64.exe                                        : 2.7.1.0
  RtlUpd.exe                                          : 2.7.1.0
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.32
  ALSndMgr.cpl                                        : 1.0.0.11
  RTSndMgr.cpl                                        : 1.0.1.0
  RTCOMDLL.dll                                        : 1.0.0.97
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5694
  AERTSrv.exe                                         : 1.0.32.7
  RtHDVCpl.exe                                        : 1.0.0.235
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd.exe                                          : 2.7.1.0
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.21
  RTSndMgr.cpl                                        : 1.0.0.9
  AERTACap.dll                                        : 1.0.32.7
  AERTARen.dll                                        : 1.0.32.3
  FMAPO.dll                                           : 40.59.0.0
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.0.13.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  RTCOMDLL.dll                                        : 2.0.0.99
  RtkAPO.dll                                          : 11.0.6000.72
  RtkApoApi.dll                                       : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.3.2
  RtkPgExt.dll                                        : 6.0.6000.54
  RtlCPAPI.dll                                        : 1.0.1.9
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5694
  AERTSr64.exe                                        : 1.0.64.7
  RAVCpl64.exe                                        : 1.0.0.235
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd64.exe                                        : 2.7.1.0
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.21
  RTSnMg64.cpl                                        : 1.0.0.9
  AERTAC64.dll                                        : 1.0.64.7
  AERTAR64.dll                                        : 1.0.64.3
  FMAPO64.dll                                         : 40.59.0.0
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  RCoInst64.dll                                       : 1.0.3.2
  RtCOM64.dll                                         : 2.0.0.99
  RTCOMDLL.dll                                        : 2.0.0.99
  RtkApi64.dll                                        : 1.0.0.4
  RtkAPO64.dll                                        : 11.0.6000.72
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.54
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5692
  RtkUpd.exe                                          : 2.7.1.0
  RHCoInst.dll                                        : 1.0.3.2
  RHDMIExt.dll                                        : 6.0.6000.54
  RtkHDMI.dll                                         : 11.0.6000.72

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5692
  RtkUpd64.exe                                        : 2.7.1.0
  RHCoInst64.dll                                      : 1.0.3.2
  RHDMEx64.dll                                        : 6.0.6000.54
  RtkHDM64.dll                                        : 11.0.6000.72

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5692
  RtkUpd.exe                                          : 2.7.1.0
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5692
  RtkUpd64.exe                                        : 2.7.1.0

  Driver Setup Program                                : 2.62
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R2.02
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272, ALC273
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272, ALC273
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
            2. Update ForteMedia microphone effect library.

        2.) Package :
            1. Delete driver file by Rtlupd.exe in Windows 2000/2003/XP System . ( Rtlupd.exe 2.7.1.0 )
            
     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5683
  RTKHDAUD.sys                                        : 5.10.0.5683
  Alcmtr.exe                                          : 1.6.0.3
  AlcWzrd.exe                                         : 1.1.0.37
  MicCal.exe                                          : 1.1.1.8
  RTHDCPL.exe                                         : 2.2.3.3
  RTLCPL.exe                                          : 1.0.1.66
  RtlUpd64.exe                                        : 2.7.1.0
  RtlUpd.exe                                          : 2.7.1.0
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.31
  ALSndMgr.cpl                                        : 1.0.0.11
  RTSndMgr.cpl                                        : 1.0.1.0
  RTCOMDLL.dll                                        : 1.0.0.97
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5683
  AERTSrv.exe                                         : 1.0.32.7
  RtHDVCpl.exe                                        : 1.0.0.227
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd.exe                                          : 2.7.1.0
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.19
  RTSndMgr.cpl                                        : 1.0.0.8
  AERTACap.dll                                        : 1.0.32.7
  AERTARen.dll                                        : 1.0.32.3
  FMAPO.dll                                           : 40.59.0.0
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.0.13.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  RTCOMDLL.dll                                        : 2.0.0.99
  RtkAPO.dll                                          : 11.0.6000.71
  RtkApoApi.dll                                       : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.3.2
  RtkPgExt.dll                                        : 6.0.6000.53
  RtlCPAPI.dll                                        : 1.0.1.9
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5683
  AERTSr64.exe                                        : 1.0.64.7
  RAVCpl64.exe                                        : 1.0.0.227
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd64.exe                                        : 2.7.1.0
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.19
  RTSnMg64.cpl                                        : 1.0.0.8
  AERTAC64.dll                                        : 1.0.64.7
  AERTAR64.dll                                        : 1.0.64.3
  FMAPO64.dll                                         : 40.59.0.0
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  RCoInst64.dll                                       : 1.0.3.2
  RtCOM64.dll                                         : 2.0.0.99
  RTCOMDLL.dll                                        : 2.0.0.99
  RtkApi64.dll                                        : 1.0.0.4
  RtkAPO64.dll                                        : 11.0.6000.71
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.53
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5668
  RtkUpd.exe                                          : 2.7.0.9
  RHCoInst.dll                                        : 1.0.2.9
  RHDMIExt.dll                                        : 6.0.6000.52
  RtkHDMI.dll                                         : 11.0.6000.69

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5668
  RtkUpd64.exe                                        : 2.7.0.9
  RHCoInst64.dll                                      : 1.0.2.9
  RHDMEx64.dll                                        : 6.0.6000.52
  RtkHDM64.dll                                        : 11.0.6000.69

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5668
  RtkUpd.exe                                          : 2.7.0.9
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5668
  RtkUpd64.exe                                        : 2.7.0.9

  Driver Setup Program                                : 2.62
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R2.01
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272, ALC273
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272, ALC273
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
            2. Support ALC273.

        2.) Package :
            1. Change warning message for upgrade driver . 
            2. ChCfg.exe add version and manifest embedded feature .
            3. Add Manifest to Rtlupd.exe and HideWin.exe . 
            4. The SetCDfmt function was included by RtlExUpd.dll Ver.1.0.1.1
            
     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5680
  RTKHDAUD.sys                                        : 5.10.0.5680
  Alcmtr.exe                                          : 1.6.0.3
  AlcWzrd.exe                                         : 1.1.0.37
  MicCal.exe                                          : 1.1.1.8
  RTHDCPL.exe                                         : 2.2.3.3
  RTLCPL.exe                                          : 1.0.1.66
  RtlUpd64.exe                                        : 2.7.0.9
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.31
  ALSndMgr.cpl                                        : 1.0.0.11
  RTSndMgr.cpl                                        : 1.0.1.0
  RTCOMDLL.dll                                        : 1.0.0.97
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5680
  AERTSrv.exe                                         : 1.0.32.7
  RtHDVCpl.exe                                        : 1.0.0.224
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.19
  RTSndMgr.cpl                                        : 1.0.0.8
  AERTACap.dll                                        : 1.0.32.7
  AERTARen.dll                                        : 1.0.32.3
  FMAPO.dll                                           : 40.59.0.0
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.0.13.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  RTCOMDLL.dll                                        : 2.0.0.99
  RtkAPO.dll                                          : 11.0.6000.71
  RtkApoApi.dll                                       : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.3.2
  RtkPgExt.dll                                        : 6.0.6000.53
  RtlCPAPI.dll                                        : 1.0.1.9
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5680
  AERTSr64.exe                                        : 1.0.64.7
  RAVCpl64.exe                                        : 1.0.0.224
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd64.exe                                        : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.19
  RTSnMg64.cpl                                        : 1.0.0.8
  AERTAC64.dll                                        : 1.0.64.7
  AERTAR64.dll                                        : 1.0.64.3
  FMAPO64.dll                                         : 40.59.0.0
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  RCoInst64.dll                                       : 1.0.3.2
  RtCOM64.dll                                         : 2.0.0.99
  RTCOMDLL.dll                                        : 2.0.0.99
  RtkApi64.dll                                        : 1.0.0.4
  RtkAPO64.dll                                        : 11.0.6000.71
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.53
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5668
  RtkUpd.exe                                          : 2.7.0.9
  RHCoInst.dll                                        : 1.0.2.9
  RHDMIExt.dll                                        : 6.0.6000.52
  RtkHDMI.dll                                         : 11.0.6000.69

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5668
  RtkUpd64.exe                                        : 2.7.0.9
  RHCoInst64.dll                                      : 1.0.2.9
  RHDMEx64.dll                                        : 6.0.6000.52
  RtkHDM64.dll                                        : 11.0.6000.69

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5668
  RtkUpd.exe                                          : 2.7.0.9
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5668
  RtkUpd64.exe                                        : 2.7.0.9

  Driver Setup Program                                : 2.61
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R2.00
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
            
     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5672
  RTKHDAUD.sys                                        : 5.10.0.5672
  Alcmtr.exe                                          : 1.6.0.3
  AlcWzrd.exe                                         : 1.1.0.37
  MicCal.exe                                          : 1.1.1.8
  RTHDCPL.exe                                         : 2.2.3.1
  RTLCPL.exe                                          : 1.0.1.66
  RtlUpd64.exe                                        : 2.7.0.9
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.31
  ALSndMgr.cpl                                        : 1.0.0.11
  RTSndMgr.cpl                                        : 1.0.1.0
  RTCOMDLL.dll                                        : 1.0.0.97
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5672
  AERTSrv.exe                                         : 1.0.32.7
  RtHDVCpl.exe                                        : 1.0.0.219
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.19
  RTSndMgr.cpl                                        : 1.0.0.8
  AERTACap.dll                                        : 1.0.32.7
  AERTARen.dll                                        : 1.0.32.3
  FMAPO.dll                                           : 40.59.0.0
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.0.13.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  RTCOMDLL.dll                                        : 2.0.0.98
  RtkAPO.dll                                          : 11.0.6000.70
  RtkApoApi.dll                                       : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.3.1
  RtkPgExt.dll                                        : 6.0.6000.53
  RtlCPAPI.dll                                        : 1.0.1.9
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5672
  AERTSr64.exe                                        : 1.0.64.7
  RAVCpl64.exe                                        : 1.0.0.219
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd64.exe                                        : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.19
  RTSnMg64.cpl                                        : 1.0.0.8
  AERTAC64.dll                                        : 1.0.64.7
  AERTAR64.dll                                        : 1.0.64.3
  FMAPO64.dll                                         : 40.59.0.0
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  RCoInst64.dll                                       : 1.0.3.1
  RtCOM64.dll                                         : 2.0.0.98
  RTCOMDLL.dll                                        : 2.0.0.98
  RtkApi64.dll                                        : 1.0.0.4
  RtkAPO64.dll                                        : 11.0.6000.70
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.53
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5668
  RtkUpd.exe                                          : 2.7.0.9
  RHCoInst.dll                                        : 1.0.2.9
  RHDMIExt.dll                                        : 6.0.6000.52
  RtkHDMI.dll                                         : 11.0.6000.69

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5668
  RtkUpd64.exe                                        : 2.7.0.9
  RHCoInst64.dll                                      : 1.0.2.9
  RHDMEx64.dll                                        : 6.0.6000.52
  RtkHDM64.dll                                        : 11.0.6000.69

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5668
  RtkUpd.exe                                          : 2.7.0.9
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5668
  RtkUpd64.exe                                        : 2.7.0.9

  Driver Setup Program                                : 2.60
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.99
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
            
     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5667
  RTKHDAUD.sys                                        : 5.10.0.5667
  MicCal.exe                                          : 1.1.1.8
  RTHDCPL.exe                                         : 2.2.3.0
  RTLCPL.exe                                          : 1.0.1.66
  RtlUpd64.exe                                        : 2.7.0.9
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.31
  Alcmtr.exe                                          : 1.6.0.3
  AlcWzrd.exe                                         : 1.1.0.37
  RTSndMgr.cpl                                        : 1.0.1.0
  ALSndMgr.cpl                                        : 1.0.0.11
  RTCOMDLL.dll                                        : 1.0.0.97
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5667
  AERTSrv.exe                                         : 1.0.32.2
  RtHDVCpl.exe                                        : 1.0.0.215
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.18
  RTSndMgr.cpl                                        : 1.0.0.8
  AERTACap.dll                                        : 1.0.32.7
  AERTARen.dll                                        : 1.0.32.3
  FMAPO.dll                                           : 40.59.0.0
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.0.13.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  RTCOMDLL.dll                                        : 2.0.0.98
  RtkAPO.dll                                          : 11.0.6000.69
  RtkApoApi.dll                                       : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.3.1
  RtkPgExt.dll                                        : 6.0.6000.52
  RtlCPAPI.dll                                        : 1.0.1.9
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5667
  AERTSr64.exe                                        : 1.0.64.2
  RAVCpl64.exe                                        : 1.0.0.215
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd64.exe                                        : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.18
  RTSnMg64.cpl                                        : 1.0.0.8
  AERTAC64.dll                                        : 1.0.64.7
  AERTAR64.dll                                        : 1.0.64.3
  FMAPO64.dll                                         : 40.59.0.0
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  RCoInst64.dll                                       : 1.0.3.1
  RtCOM64.dll                                         : 2.0.0.98
  RTCOMDLL.dll                                        : 2.0.0.98
  RtkApi64.dll                                        : 1.0.0.4
  RtkAPO64.dll                                        : 11.0.6000.69
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.52
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5645
  RtkUpd.exe                                          : 2.7.0.9
  RHCoInst.dll                                        : 1.0.2.9
  RHDMIExt.dll                                        : 6.0.6000.50
  RtkHDMI.dll                                         : 11.0.6000.67

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5645
  RtkUpd64.exe                                        : 2.7.0.9
  RHCoInst64.dll                                      : 1.0.2.9
  RHDMEx64.dll                                        : 6.0.6000.50
  RtkHDM64.dll                                        : 11.0.6000.67

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5645
  RtkUpd.exe                                          : 2.7.0.9
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5645
  RtkUpd64.exe                                        : 2.7.0.9

  Driver Setup Program                                : 2.60
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.98
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
            2. Fix the potential risk that audio driver can't be installed completely under Vista.

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5657
  RTKHDAUD.sys                                        : 5.10.0.5657
  Alcmtr.exe                                          : 1.6.0.3
  AlcWzrd.exe                                         : 1.1.0.37
  MicCal.exe                                          : 1.1.1.8
  RTHDCPL.exe                                         : 2.2.2.5
  RTLCPL.exe                                          : 1.0.1.66
  RtlUpd64.exe                                        : 2.7.0.9
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.31
  ALSndMgr.cpl                                        : 1.0.0.11
  RTSndMgr.cpl                                        : 1.0.1.0
  RTCOMDLL.dll                                        : 1.0.0.97
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5657
  AERTSrv.exe                                         : 1.0.32.2
  RtHDVCpl.exe                                        : 1.0.0.208
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.14
  RTSndMgr.cpl                                        : 1.0.0.8
  AERTACap.dll                                        : 1.0.32.7
  AERTARen.dll                                        : 1.0.32.3
  FMAPO.dll                                           : 40.59.0.0
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.0.13.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  RTCOMDLL.dll                                        : 2.0.0.98
  RtkAPO.dll                                          : 11.0.6000.69
  RtkApoApi.dll                                       : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.2.10
  RtkPgExt.dll                                        : 6.0.6000.52
  RtlCPAPI.dll                                        : 1.0.1.9
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5657
  AERTSr64.exe                                        : 1.0.64.2
  RAVCpl64.exe                                        : 1.0.0.208
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd64.exe                                        : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.14
  RTSnMg64.cpl                                        : 1.0.0.8
  AERTAC64.dll                                        : 1.0.64.7
  AERTAR64.dll                                        : 1.0.64.3
  FMAPO64.dll                                         : 40.59.0.0
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  RCoInst64.dll                                       : 1.0.2.10
  RtCOM64.dll                                         : 2.0.0.98
  RTCOMDLL.dll                                        : 2.0.0.98
  RtkApi64.dll                                        : 1.0.0.4
  RtkAPO64.dll                                        : 11.0.6000.69
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.52
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5645
  RtkUpd.exe                                          : 2.7.0.9
  RHCoInst.dll                                        : 1.0.2.9
  RHDMIExt.dll                                        : 6.0.6000.50
  RtkHDMI.dll                                         : 11.0.6000.67

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5645
  RtkUpd64.exe                                        : 2.7.0.9
  RHCoInst64.dll                                      : 1.0.2.9
  RHDMEx64.dll                                        : 6.0.6000.50
  RtkHDM64.dll                                        : 11.0.6000.67

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5645
  RtkUpd.exe                                          : 2.7.0.9
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5645
  RtkUpd64.exe                                        : 2.7.0.9

  Driver Setup Program                                : 2.60
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.97
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
            2. Add 24-bits recording feature.
            3. Fix EAX direct parameter issue under XP.
            4. Fix dummy noise issue under XP.

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5653
  RTKHDAUD.sys                                        : 5.10.0.5653
  Alcmtr.exe                                          : 1.6.0.3
  AlcWzrd.exe                                         : 1.1.0.37
  MicCal.exe                                          : 1.1.1.8
  RTHDCPL.exe                                         : 2.2.2.4
  RTLCPL.exe                                          : 1.0.1.66
  RtlUpd64.exe                                        : 2.7.0.9
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.31
  ALSndMgr.cpl                                        : 1.0.0.11
  RTSndMgr.cpl                                        : 1.0.1.0
  RTCOMDLL.dll                                        : 1.0.0.97
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5653
  AERTSrv.exe                                         : 1.0.32.2
  RtHDVCpl.exe                                        : 1.0.0.206
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.12
  RTSndMgr.cpl                                        : 1.0.0.8
  AERTACap.dll                                        : 1.0.32.7
  AERTARen.dll                                        : 1.0.32.3
  FMAPO.dll                                           : 40.59.0.0
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.0.13.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  RTCOMDLL.dll                                        : 2.0.0.98
  RtkAPO.dll                                          : 11.0.6000.67
  RtkApoApi.dll                                       : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.2.10
  RtkPgExt.dll                                        : 6.0.6000.50
  RtlCPAPI.dll                                        : 1.0.1.9
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5653
  AERTSr64.exe                                        : 1.0.64.2
  RAVCpl64.exe                                        : 1.0.0.206
  RtkAudioService.exe                                 : 1.0.0.16
  RtlUpd64.exe                                        : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.1
  vncutil.exe                                         : 1.0.0.12
  RTSnMg64.cpl                                        : 1.0.0.8
  AERTAC64.dll                                        : 1.0.64.7
  AERTAR64.dll                                        : 1.0.64.3
  FMAPO64.dll                                         : 40.59.0.0
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  RCoInst64.dll                                       : 1.0.2.10
  RtCOM64.dll                                         : 2.0.0.98
  RTCOMDLL.dll                                        : 2.0.0.98
  RtkApi64.dll                                        : 1.0.0.4
  RtkAPO64.dll                                        : 11.0.6000.67
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.50
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5645
  RtkUpd.exe                                          : 2.7.0.9
  RHCoInst.dll                                        : 1.0.2.9
  RHDMIExt.dll                                        : 6.0.6000.50
  RtkHDMI.dll                                         : 11.0.6000.67

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5645
  RtkUpd64.exe                                        : 2.7.0.9
  RHCoInst64.dll                                      : 1.0.2.9
  RHDMEx64.dll                                        : 6.0.6000.50
  RtkHDM64.dll                                        : 11.0.6000.67

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5645
  RtkUpd.exe                                          : 2.7.0.9
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5645
  RtkUpd64.exe                                        : 2.7.0.9

  Driver Setup Program                                : 2.60
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.96
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.

        2.) Package :
            1. Fix uninstalled message_2 problem ( French language ) .

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5643
  RTKHDAUD.sys                                        : 5.10.0.5643
  Alcmtr.exe                                          : 1.6.0.2
  AlcWzrd.exe                                         : 1.1.0.36
  MicCal.exe                                          : 1.1.1.8
  RTHDCPL.exe                                         : 2.2.1.8
  RTLCPL.exe                                          : 1.0.1.65
  RtlUpd64.exe                                        : 2.7.0.9
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.30
  ALSndMgr.cpl                                        : 1.0.0.10
  RTSndMgr.cpl                                        : 1.0.1.0
  RTCOMDLL.dll                                        : 1.0.0.97
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5643
  AERTSrv.exe                                         : 1.0.32.2
  RtHDVCpl.exe                                        : 1.0.0.198
  RtkAudioService.exe                                 : 1.0.0.14
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  vncutil.exe                                         : 1.0.0.7
  RTSndMgr.cpl                                        : 1.0.0.8
  AERTACap.dll                                        : 1.0.32.7
  AERTARen.dll                                        : 1.0.32.3
  FMAPO.dll                                           : 40.59.0.0
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.0.13.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  RTCOMDLL.dll                                        : 2.0.0.98
  RtkAPO.dll                                          : 11.0.6000.67
  RtkApoApi.dll                                       : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.2.6
  RtkPgExt.dll                                        : 6.0.6000.49
  RtlCPAPI.dll                                        : 1.0.1.9
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5643
  AERTSr64.exe                                        : 1.0.64.2
  RAVCpl64.exe                                        : 1.0.0.198
  RtkAudioService.exe                                 : 1.0.0.14
  RtlUpd64.exe                                        : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  vncutil.exe                                         : 1.0.0.7
  RTSnMg64.cpl                                        : 1.0.0.8
  AERTAC64.dll                                        : 1.0.64.7
  AERTAR64.dll                                        : 1.0.64.3
  FMAPO64.dll                                         : 40.59.0.0
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  RCoInst64.dll                                       : 1.0.2.6
  RtCOM64.dll                                         : 2.0.0.98
  RTCOMDLL.dll                                        : 2.0.0.98
  RtkApi64.dll                                        : 1.0.0.4
  RtkAPO64.dll                                        : 11.0.6000.67
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.49
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5633
  RtkUpd.exe                                          : 2.7.0.9
  RHDMIExt.dll                                        : 6.0.6000.48
  RtkHDMI.dll                                         : 11.0.6000.66

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5633
  RtkUpd64.exe                                        : 2.7.0.9
  RHDMEx64.dll                                        : 6.0.6000.48
  RtkHDM64.dll                                        : 11.0.6000.66

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5633
  RtkUpd.exe                                          : 2.7.0.9
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5633
  RtkUpd64.exe                                        : 2.7.0.9

  Driver Setup Program                                : 2.60
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.95
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
            2. Fix encryption stream issue for ALC889.
            3. Fix DRM issue. 

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5636
  RTKHDAUD.sys                                        : 5.10.0.5636
  Alcmtr.exe                                          : 1.6.0.2
  AlcWzrd.exe                                         : 1.1.0.36
  MicCal.exe                                          : 1.1.1.8
  RTHDCPL.exe                                         : 2.2.1.6
  RTLCPL.exe                                          : 1.0.1.65
  RtlUpd64.exe                                        : 2.7.0.9
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.30
  ALSndMgr.cpl                                        : 1.0.0.10
  RTSndMgr.cpl                                        : 1.0.1.0
  RTCOMDLL.dll                                        : 1.0.0.96
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  RTKVHDA.sys                                         : 6.0.1.5636
  AERTSrv.exe                                         : 1.0.32.2
  RtHDVCpl.exe                                        : 1.0.0.192
  RtkAudioService.exe                                 : 1.0.0.12
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  vncutil.exe                                         : 1.0.0.5
  RTSndMgr.cpl                                        : 1.0.0.8
  AERTACap.dll                                        : 1.0.32.7
  AERTARen.dll                                        : 1.0.32.3
  FMAPO.dll                                           : 40.59.0.0
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.0.13.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  RTCOMDLL.dll                                        : 2.0.0.98
  RtkAPO.dll                                          : 11.0.6000.66
  RtkApoApi.dll                                       : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.2.5
  RtkPgExt.dll                                        : 6.0.6000.48
  RtlCPAPI.dll                                        : 1.0.1.9
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5636
  AERTSr64.exe                                        : 1.0.64.2
  RAVCpl64.exe                                        : 1.0.0.192
  RtkAudioService.exe                                 : 1.0.0.12
  RtlUpd64.exe                                        : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  vncutil.exe                                         : 1.0.0.5
  RTSnMg64.cpl                                        : 1.0.0.8
  AERTAC64.dll                                        : 1.0.64.7
  AERTAR64.dll                                        : 1.0.64.3
  FMAPO64.dll                                         : 40.59.0.0
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  RCoInst64.dll                                       : 1.0.2.5
  RtCOM64.dll                                         : 2.0.0.98
  RTCOMDLL.dll                                        : 2.0.0.98
  RtkApi64.dll                                        : 1.0.0.4
  RtkAPO64.dll                                        : 11.0.6000.66
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.48
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5612
  RtkUpd.exe                                          : 2.7.0.9
  RHDMIExt.dll                                        : 6.0.6000.44
  RtkHDMI.dll                                         : 11.0.6000.63

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5612
  RtkUpd64.exe                                        : 2.7.0.9
  RHDMEx64.dll                                        : 6.0.6000.44
  RtkHDM64.dll                                        : 11.0.6000.63

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5612
  RtkUpd.exe                                          : 2.7.0.9

  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5612
  RtkUpd64.exe                                        : 2.7.0.9

  Driver Setup Program                                : 2.59
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.94
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
            2. Zero recorded data for SPDIF-IN copy-protection stream under Vista.

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5628
  RTKHDAUD.sys                                        : 5.10.0.5628
  Alcmtr.exe                                          : 1.6.0.2
  AlcWzrd.exe                                         : 1.1.0.36
  MicCal.exe                                          : 1.1.1.8
  RTHDCPL.exe                                         : 2.2.1.3
  RTLCPL.exe                                          : 1.0.1.65
  RtlUpd.exe                                          : 2.7.0.9
  RtlUpd64.exe                                        : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.30
  ALSndMgr.cpl                                        : 1.0.0.10
  RTSndMgr.cpl                                        : 1.0.1.0
  RTCOMDLL.dll                                        : 1.0.0.96
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  RTKVHDA.sys                                         : 6.0.1.5628
  AERTSrv.exe                                         : 1.0.32.2
  RtHDVCpl.exe                                        : 1.0.0.188
  RtkAudioService.exe                                 : 1.0.0.12
  RtkSmbus.exe                                        : 1.0.0.2
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  RTSndMgr.cpl                                        : 1.0.0.8
  AERTACap.dll                                        : 1.0.32.7
  AERTARen.dll                                        : 1.0.32.3
  FMAPO.dll                                           : 40.59.0.0
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.0.13.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  RTCOMDLL.dll                                        : 2.0.0.97
  RtkAPO.dll                                          : 11.0.6000.65
  RtkApoApi.dll                                       : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.2.3
  RtkPgExt.dll                                        : 6.0.6000.47
  RtlCPAPI.dll                                        : 1.0.1.9
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5628
  AERTSr64.exe                                        : 1.0.64.2
  RAVCpl64.exe                                        : 1.0.0.188
  RtkAudioService.exe                                 : 1.0.0.12
  RtkSmbus.exe                                        : 1.0.0.2
  RtlUpd64.exe                                        : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  RTSnMg64.cpl                                        : 1.0.0.8
  AERTAC64.dll                                        : 1.0.64.7
  AERTAR64.dll                                        : 1.0.64.3
  FMAPO64.dll                                         : 40.59.0.0
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  RCoInst64.dll                                       : 1.0.2.3
  RtCOM64.dll                                         : 2.0.0.97
  RTCOMDLL.dll                                        : 2.0.0.97
  RtkApi64.dll                                        : 1.0.0.4
  RtkAPO64.dll                                        : 11.0.6000.65
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.47
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5612
  RtkUpd.exe                                          : 2.7.0.9
  RHDMIExt.dll                                        : 6.0.6000.44
  RtkHDMI.dll                                         : 11.0.6000.63

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5612
  RtkUpd64.exe                                        : 2.7.0.9
  RHDMEx64.dll                                        : 6.0.6000.44
  RtkHDM64.dll                                        : 11.0.6000.63

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5612
  RtkUpd.exe                                          : 2.7.0.9

  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5612
  RtkUpd64.exe                                        : 2.7.0.9

  Driver Setup Program                                : 2.59
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.93
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
        2.) Package :
            1. Small VGA mode should not be checked in silent installation . 

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5624
  RTKHDAUD.sys                                        : 5.10.0.5624
  Alcmtr.exe                                          : 1.6.0.2
  AlcWzrd.exe                                         : 1.1.0.36
  MicCal.exe                                          : 1.1.1.8
  RTHDCPL.exe                                         : 2.2.1.1
  RTLCPL.exe                                          : 1.0.1.65
  RtlUpd64.exe                                        : 2.7.0.9
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.30
  ALSndMgr.cpl                                        : 1.0.0.10
  RTSndMgr.cpl                                        : 1.0.1.0
  RTCOMDLL.dll                                        : 1.0.0.96
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  RTKVHDA.sys                                         : 6.0.1.5624
  AERTSrv.exe                                         : 1.0.32.2
  RtHDVCpl.exe                                        : 1.0.0.185
  RtkAudioService.exe                                 : 1.0.0.12
  RtkSmbus.exe                                        : 1.0.0.2
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  RTSndMgr.cpl                                        : 1.0.0.7
  AERTACap.dll                                        : 1.0.32.7
  AERTARen.dll                                        : 1.0.32.3
  FMAPO.dll                                           : 40.59.0.0
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.0.13.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  RTCOMDLL.dll                                        : 2.0.0.97
  RtkAPO.dll                                          : 11.0.6000.65
  RtkApoApi.dll                                       : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.2.3
  RtkPgExt.dll                                        : 6.0.6000.46
  RtlCPAPI.dll                                        : 1.0.1.9
  SRSHP360.dll                                        : 1.1.0.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5624
  AERTSr64.exe                                        : 1.0.64.2
  RAVCpl64.exe                                        : 1.0.0.185
  RtkAudioService.exe                                 : 1.0.0.12
  RtkSmbus.exe                                        : 1.0.0.2
  RtlUpd64.exe                                        : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  RTSnMg64.cpl                                        : 1.0.0.7
  AERTAC64.dll                                        : 1.0.64.7
  AERTAR64.dll                                        : 1.0.64.3
  FMAPO64.dll                                         : 40.59.0.0
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  RCoInst64.dll                                       : 1.0.2.3
  RtCOM64.dll                                         : 2.0.0.97
  RTCOMDLL.dll                                        : 2.0.0.97
  RtkApi64.dll                                        : 1.0.0.4
  RtkAPO64.dll                                        : 11.0.6000.65
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.46
  SRSHP64.dll                                         : 1.1.0.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5612
  RtkUpd.exe                                          : 2.7.0.9
  RHDMIExt.dll                                        : 6.0.6000.44
  RtkHDMI.dll                                         : 11.0.6000.63

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5612
  RtkUpd64.exe                                        : 2.7.0.9
  RHDMEx64.dll                                        : 6.0.6000.44
  RtkHDM64.dll                                        : 11.0.6000.63

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5612
  RtkUpd.exe                                          : 2.7.0.9

  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5612
  RtkUpd64.exe                                        : 2.7.0.9

  Driver Setup Program                                : 2.59
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.92
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Fix Stereo Mix issue with codec which support capless output pin.
            2. Customizations.

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5618
  RTKHDAUD.sys                                        : 5.10.0.5618
  MicCal.exe                                          : 1.1.1.8
  RTHDCPL.exe                                         : 2.2.1.0
  RTLCPL.exe                                          : 1.0.1.65
  RtlUpd64.exe                                        : 2.7.0.9
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.30
  Alcmtr.exe                                          : 1.6.0.2
  AlcWzrd.exe                                         : 1.1.0.36
  RTSndMgr.cpl                                        : 1.0.1.0
  ALSndMgr.cpl                                        : 1.0.0.10
  RTCOMDLL.dll                                        : 1.0.0.96
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5618
  AERTSrv.exe                                         : 1.0.32.2
  RtHDVCpl.exe                                        : 1.0.0.183
  RtkAudioService.exe                                 : 1.0.0.12
  RtkSmbus.exe                                        : 1.0.0.2
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  RTSndMgr.cpl                                        : 1.0.0.7
  AERTACap.dll                                        : 1.0.32.7
  AERTARen.dll                                        : 1.0.32.3
  FMAPO.dll                                           : 40.58.0.0
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.0.13.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  RTCOMDLL.dll                                        : 2.0.0.97
  RtkAPO.dll                                          : 11.0.6000.64
  RtkApoApi.dll                                       : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.2.1
  RtkPgExt.dll                                        : 6.0.6000.45
  RtlCPAPI.dll                                        : 1.0.1.9
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5618
  AERTSr64.exe                                        : 1.0.64.2
  RAVCpl64.exe                                        : 1.0.0.183
  RtkAudioService.exe                                 : 1.0.0.12
  RtkSmbus.exe                                        : 1.0.0.2
  RtlUpd64.exe                                        : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  RTSnMg64.cpl                                        : 1.0.0.7
  AERTAC64.dll                                        : 1.0.64.7
  AERTAR64.dll                                        : 1.0.64.3
  FMAPO64.dll                                         : 40.58.0.0
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  RCoInst64.dll                                       : 1.0.2.1
  RtCOM64.dll                                         : 2.0.0.97
  RTCOMDLL.dll                                        : 2.0.0.97
  RtkApi64.dll                                        : 1.0.0.4
  RtkAPO64.dll                                        : 11.0.6000.64
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.45
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5612
  RtkUpd.exe                                          : 2.7.0.9
  RHDMIExt.dll                                        : 6.0.6000.44
  RtkHDMI.dll                                         : 11.0.6000.63

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5612
  RtkUpd64.exe                                        : 2.7.0.9
  RHDMEx64.dll                                        : 6.0.6000.44
  RtkHDM64.dll                                        : 11.0.6000.63

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5612
  RtkUpd.exe                                          : 2.7.0.9

  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5612
  RtkUpd64.exe                                        : 2.7.0.9

  Driver Setup Program                                : 2.58
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.91
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Fix DTM 1.2 KS topology test fail issue.
            2. Customizations.

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  RTKHDA64.sys                                        : 5.10.0.5605
  RTKHDAUD.sys                                        : 5.10.0.5605
  MicCal.exe                                          : 1.1.1.8
  RTHDCPL.exe                                         : 2.2.0.2
  RTLCPL.exe                                          : 1.0.1.65
  RtlUpd64.exe                                        : 2.7.0.9
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  SoundMan.exe                                        : 1.0.0.30
  Alcmtr.exe                                          : 1.6.0.2
  AlcWzrd.exe                                         : 1.1.0.36
  RTSndMgr.cpl                                        : 1.0.1.0
  ALSndMgr.cpl                                        : 1.0.0.10
  RTCOMDLL.dll                                        : 1.0.0.96
  RtlCPAPI.dll                                        : 1.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86
  RTKVHDA.sys                                         : 6.0.1.5605
  AERTSrv.exe                                         : 1.0.32.2
  RtHDVCpl.exe                                        : 1.0.0.172
  RtkAudioService.exe                                 : 1.0.0.11
  RtkSmbus.exe                                        : 1.0.0.1
  RtlUpd.exe                                          : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  RTSndMgr.cpl                                        : 1.0.0.7
  AERTACap.dll                                        : 1.0.32.7
  AERTARen.dll                                        : 1.0.32.3
  FMAPO.dll                                           : 6.0.6000.16386
  MaxxAudioAPO.dll                                    : 1.2.2.0
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  MaxxAudioEQ.dll                                     : 5.9.7.0
  RTCOMDLL.dll                                        : 2.0.0.96
  RtkAPO.dll                                          : 11.0.6000.63
  RtkApoApi.dll                                       : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.2.0
  RtkPgExt.dll                                        : 6.0.6000.42
  RtlCPAPI.dll                                        : 1.0.1.9
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  WavesLib.dll                                        : 5.9.7.0
  Vista driver for x64
  RTKVHD64.sys                                        : 6.0.1.5605
  AERTSr64.exe                                        : 1.0.64.2
  RAVCpl64.exe                                        : 1.0.0.172
  RtkAudioService.exe                                 : 1.0.0.11
  RtkSmbus.exe                                        : 1.0.0.1
  RtlUpd64.exe                                        : 2.7.0.9
  SkyTel.exe                                          : 2.0.2.0
  RTSnMg64.cpl                                        : 1.0.0.7
  AERTAC64.dll                                        : 1.0.64.7
  AERTAR64.dll                                        : 1.0.64.3
  FMAPO64.dll                                         : 6.0.6000.16386
  MaxxAudioAPO20.dll                                  : 2.0.12.0
  RCoInst64.dll                                       : 1.0.2.0
  RtCOM64.dll                                         : 2.0.0.96
  RTCOMDLL.dll                                        : 2.0.0.96
  RtkApi64.dll                                        : 1.0.0.4
  RtkAPO64.dll                                        : 11.0.6000.63
  RtlCPAPI.dll                                        : 1.0.1.9
  RtPgEx64.dll                                        : 6.0.6000.42
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
HDMI Driver : ---------------------------------------------------------
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5602
  RtkUpd.exe                                          : 2.7.0.9
  RHDMIExt.dll                                        : 6.0.6000.42
  RtkHDMI.dll                                         : 11.0.6000.62

  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5602
  RtkUpd64.exe                                        : 2.7.0.9
  RHDMEx64.dll                                        : 6.0.6000.42
  RtkHDM64.dll                                        : 11.0.6000.62

  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5602
  RtkUpd.exe                                          : 2.7.0.9

  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5602
  RtkUpd64.exe                                        : 2.7.0.9

  Driver Setup Program                                : 2.58
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.90
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262,ALC267, ALC268, ALC269, ALC272
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC663, ALC260, ALC262, ALC267,ALC268, ALC269, ALC272
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Support ALC663/ALC272.
            2. Support ForteMedia microphone effect APO feature.
            3. Customizations.

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5591
  WDM driver for Winx64                               : 5.10.0.5591
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.1.0
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.9.6
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.2.0
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5591
  RtHDVCpl.exe                                        : 1.0.0.159
  RtkAPO.dll                                          : 11.0.6000.60
  RtkPgExt.dll                                        : 6.0.6000.40
  RTCOMDLL.dll                                        : 2.0.0.96
  RtlCPAPI.dll                                        : 1.0.1.8
  RTSndMgr.cpl                                        : 1.0.0.7
  RtkCoInst.dll                                       : 1.0.1.29
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.3
  Vista driver for x64                                : 6.0.1.5591
  RAVCpl64.exe                                        : 1.0.0.159
  RtkAPO64.dll                                        : 11.0.6000.60
  RtPgEx64.dll                                        : 6.0.6000.40
  RTCOMDLL.dll                                        : 2.0.0.96
  RtlCPAPI.dll                                        : 1.0.1.8
  RTSnMg64.cpl                                        : 1.0.0.7
  RCoInst64.dll                                       : 1.0.1.29
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.3
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5575
  RtkHDM64.dll                                        : 6.0.6000.57
  RHDMEx64.dll                                        : 6.0.6000.39
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5575
  RtkHDMI.dll                                         : 6.0.6000.57
  RHDMIExt.dll                                        : 6.0.6000.39
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5575
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5575

  Driver Setup Program                                : 2.57
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.89
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268, ALC269
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268, ALC269
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Support "Event/Notification mode" under Vista.
            2. Fix Vista GUI issue when video adapter's resolution is low.
            3. Customizations.
        2.) Package :
            1. Uninstallation language selected by OS system .
            2. "Uninstall" word issue in Japanese language .

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5582
  WDM driver for Winx64                               : 5.10.0.5582
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.9.3
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.2.0
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5582
  RtHDVCpl.exe                                        : 1.0.0.153
  RtkAPO.dll                                          : 11.0.6000.59
  RtkPgExt.dll                                        : 6.0.6000.40
  RTCOMDLL.dll                                        : 2.0.0.93
  RtlCPAPI.dll                                        : 1.0.1.7
  RTSndMgr.cpl                                        : 1.0.0.7
  RtkCoInst.dll                                       : 1.0.1.27
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.3
  Vista driver for x64                                : 6.0.1.5582
  RAVCpl64.exe                                        : 1.0.0.153
  RtkAPO64.dll                                        : 11.0.6000.59
  RtPgEx64.dll                                        : 6.0.6000.40
  RTCOMDLL.dll                                        : 2.0.0.93
  RtlCPAPI.dll                                        : 1.0.1.7
  RTSnMg64.cpl                                        : 1.0.0.7
  RCoInst64.dll                                       : 1.0.1.27
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.3
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5575
  RtkHDM64.dll                                        : 6.0.6000.57
  RHDMEx64.dll                                        : 6.0.6000.39
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5575
  RtkHDMI.dll                                         : 6.0.6000.57
  RHDMIExt.dll                                        : 6.0.6000.39
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5575
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5575

  Driver Setup Program                                : 2.56
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.88
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268, ALC269
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268, ALC269
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Fix BSOD issue for WLK 1.1 System-Common Scenario Stress With IO test and System-Disable Enable With IO test under XP.
            2. Customizations.

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5574
  WDM driver for Winx64                               : 5.10.0.5574
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.9.1
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.2.0
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5574
  RtHDVCpl.exe                                        : 1.0.0.145
  RtkAPO.dll                                          : 11.0.6000.58
  RtkPgExt.dll                                        : 6.0.6000.38
  RTCOMDLL.dll                                        : 2.0.0.90
  RtlCPAPI.dll                                        : 1.0.1.7
  RTSndMgr.cpl                                        : 1.0.0.7
  RtkCoInst.dll                                       : 1.0.1.25
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.3
  Vista driver for x64                                : 6.0.1.5574
  RAVCpl64.exe                                        : 1.0.0.145
  RtkAPO64.dll                                        : 11.0.6000.58
  RtPgEx64.dll                                        : 6.0.6000.38
  RTCOMDLL.dll                                        : 2.0.0.90
  RtlCPAPI.dll                                        : 1.0.1.7
  RTSnMg64.cpl                                        : 1.0.0.7
  RCoInst64.dll                                       : 1.0.1.25
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.3
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.55
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.87
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268, ALC269
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268, ALC269
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Fix recording issue for ALC269.
            2. Customizations.

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5567
  WDM driver for Winx64                               : 5.10.0.5567
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.8.9
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.2.0
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5567
  RtHDVCpl.exe                                        : 1.0.0.139
  RtkAPO.dll                                          : 11.0.6000.56
  RtkPgExt.dll                                        : 6.0.6000.35
  RTCOMDLL.dll                                        : 2.0.0.89
  RtlCPAPI.dll                                        : 1.0.1.7
  RTSndMgr.cpl                                        : 1.0.0.7
  RtkCoInst.dll                                       : 1.0.1.25
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.3
  Vista driver for x64                                : 6.0.1.5567
  RAVCpl64.exe                                        : 1.0.0.139
  RtkAPO64.dll                                        : 11.0.6000.56
  RtPgEx64.dll                                        : 6.0.6000.35
  RTCOMDLL.dll                                        : 2.0.0.89
  RtlCPAPI.dll                                        : 1.0.1.7
  RTSnMg64.cpl                                        : 1.0.0.7
  RCoInst64.dll                                       : 1.0.1.25
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.3
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.54
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.86
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268, ALC269
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC889, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268, ALC269
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Fix the issue that SPDIF-out device broadcast 2nd output device's stream when turn on multi-streaming under Windows XP.
            2. Indexed DRC file supported.
            3. Customizations.
        2.) Package :
            1. Installer failed code.
            2. Copy .dat file rule.

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5559
  WDM driver for Winx64                               : 5.10.0.5559
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.8.7
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.2.0
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5559
  RtHDVCpl.exe                                        : 1.0.0.132
  RtkAPO.dll                                          : 11.0.6000.54
  RtkPgExt.dll                                        : 6.0.6000.35
  RTCOMDLL.dll                                        : 2.0.0.87
  RtlCPAPI.dll                                        : 1.0.1.7
  RTSndMgr.cpl                                        : 1.0.0.7
  RtkCoInst.dll                                       : 1.0.1.25
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.3
  Vista driver for x64                                : 6.0.1.5559
  RAVCpl64.exe                                        : 1.0.0.132
  RtkAPO64.dll                                        : 11.0.6000.54
  RtPgEx64.dll                                        : 6.0.6000.35
  RTCOMDLL.dll                                        : 2.0.0.87
  RtlCPAPI.dll                                        : 1.0.1.7
  RTSnMg64.cpl                                        : 1.0.0.7
  RCoInst64.dll                                       : 1.0.1.25
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.3
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.52
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.85
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268, ALC269
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268, ALC269
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Fix PC-Beep mute issue for ALC268/ALC267.
            2. Fix the potential risk that system-thread is still running when driver is already unloaded under Vista.
            3. Customizations.

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5548
  WDM driver for Winx64                               : 5.10.0.5548
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.8.6
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.2.0
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5548
  RtHDVCpl.exe                                        : 1.0.0.128
  RtkAPO.dll                                          : 11.0.6000.51
  RtkPgExt.dll                                        : 6.0.6000.33
  RTCOMDLL.dll                                        : 2.0.0.86
  RtlCPAPI.dll                                        : 1.0.1.7
  RTSndMgr.cpl                                        : 1.0.0.7
  RtkCoInst.dll                                       : 1.0.1.25
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.3
  Vista driver for x64                                : 6.0.1.5548
  RAVCpl64.exe                                        : 1.0.0.128
  RtkAPO64.dll                                        : 11.0.6000.51
  RtPgEx64.dll                                        : 6.0.6000.33
  RTCOMDLL.dll                                        : 2.0.0.86
  RtlCPAPI.dll                                        : 1.0.1.7
  RTSnMg64.cpl                                        : 1.0.0.7
  RCoInst64.dll                                       : 1.0.1.25
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.3
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.51
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.84
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268, ALC269
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268, ALC269
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Fix potential risk for re-direct headphone mode under Vista.
            2. Customizations.

     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5532
  WDM driver for Winx64                               : 5.10.0.5532
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.8.2
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.2.0
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5532
  RtHDVCpl.exe                                        : 1.0.0.116
  RtkAPO.dll                                          : 11.0.6000.48
  RtkPgExt.dll                                        : 6.0.6000.31
  RTCOMDLL.dll                                        : 2.0.0.86
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.7
  RtkCoInst.dll                                       : 1.0.1.18
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5532
  RAVCpl64.exe                                        : 1.0.0.116
  RtkAPO64.dll                                        : 11.0.6000.48
  RtPgEx64.dll                                        : 6.0.6000.31
  RTCOMDLL.dll                                        : 2.0.0.86
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.7
  RCoInst64.dll                                       : 1.0.1.18
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.2
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.51
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.83
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268, ALC269
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268, ALC269
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Support ALC269.
            2. Customizations.
            3. Turn on amplifier mask control for ALC885.
            4. Fix volume issue when turn on "Limited Output" feature under Windows XP.
     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5523
  WDM driver for Winx64                               : 5.10.0.5523
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.7.7
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.2.0
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5523
  RtHDVCpl.exe                                        : 1.0.0.112
  RtkAPO.dll                                          : 11.0.6000.48
  RtkPgExt.dll                                        : 6.0.6000.31
  RTCOMDLL.dll                                        : 2.0.0.85
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.7
  RtkCoInst.dll                                       : 1.0.1.15
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5523
  RAVCpl64.exe                                        : 1.0.0.112
  RtkAPO64.dll                                        : 11.0.6000.48
  RtPgEx64.dll                                        : 6.0.6000.31
  RTCOMDLL.dll                                        : 2.0.0.85
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.7
  RCoInst64.dll                                       : 1.0.1.15
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.2
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.51
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.82
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Support IMiniportWaveRTStreamNotification interface under Vista.
            2. Customizations.
            3. Fix bug for the specific customer. 
        2.) Installer :
            1. Add silent uninstall option .
     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5512
  WDM driver for Winx64                               : 5.10.0.5512
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.7.1
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.21
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5512
  RtHDVCpl.exe                                        : 1.0.0.106
  RtkAPO.dll                                          : 11.0.6000.48
  RtkPgExt.dll                                        : 6.0.6000.31
  RTCOMDLL.dll                                        : 2.0.0.83
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.7
  RtkCoInst.dll                                       : 1.0.1.13
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5512
  RAVCpl64.exe                                        : 1.0.0.106
  RtkAPO64.dll                                        : 11.0.6000.48
  RtPgEx64.dll                                        : 6.0.6000.31
  RTCOMDLL.dll                                        : 2.0.0.83
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.7
  RCoInst64.dll                                       : 1.0.1.13
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.2
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.51
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.81
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Support real 2.1 output capability under Vista.
            2. Improve Doppler effect for XP driver.
            3. Fix Vista DTM topology testing issue.
            4. Fix dead lock issue when more than 3 jacks set as headphone output under XP.
        2.) Installer :
            1. VSS event error for InstallShield .
     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5506
  WDM driver for Winx64                               : 5.10.0.5506
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.7.0
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.21
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5506
  RtHDVCpl.exe                                        : 1.0.0.103
  RtkAPO.dll                                          : 11.0.6000.48
  RtkPgExt.dll                                        : 6.0.6000.31
  RTCOMDLL.dll                                        : 2.0.0.82
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.6
  RtkCoInst.dll                                       : 1.0.1.13
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5506
  RAVCpl64.exe                                        : 1.0.0.103
  RtkAPO64.dll                                        : 11.0.6000.48
  RtPgEx64.dll                                        : 6.0.6000.31
  RTCOMDLL.dll                                        : 2.0.0.82
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.6
  RCoInst64.dll                                       : 1.0.1.13
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.2
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.50
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.80
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
            2. Add new feature to smooth gap between 2 different output stream under Vista.
        2.) Installer :
            1. "Program Compatibility Assistant" issue for InstallShield 11.5 .
            2. VSR stop setting .
     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5497
  WDM driver for Winx64                               : 5.10.0.5497
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.6.7
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.21
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5497
  RtHDVCpl.exe                                        : 1.0.0.99
  RtkAPO.dll                                          : 11.0.6000.45
  RtkPgExt.dll                                        : 6.0.6000.30
  RTCOMDLL.dll                                        : 2.0.0.80
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.6
  RtkCoInst.dll                                       : 1.0.1.10
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5497
  RAVCpl64.exe                                        : 1.0.0.99
  RtkAPO64.dll                                        : 11.0.6000.45
  RtPgEx64.dll                                        : 6.0.6000.30
  RTCOMDLL.dll                                        : 2.0.0.80
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.6
  RCoInst64.dll                                       : 1.0.1.10
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.2
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.49
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.79
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Driver :
            1. Customizations.
            2. Fix potential risk from dividing by zero while the input signal power approach zero under Windows XP.
            3. Support digital mic software boost for ALC888.
        2.) Installer :
            1. Remove Realtek registry key in upgrade mode.
            2. Change MCE GUI installation procedure for Windows Vista by Microsoft requirement.
            3. Add install procedure for VSR feature.
     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5490
  WDM driver for Winx64                               : 5.10.0.5490
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.6.2
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.20
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5490
  RtHDVCpl.exe                                        : 1.0.0.96
  RtkAPO.dll                                          : 11.0.6000.45
  RtkPgExt.dll                                        : 6.0.6000.30
  RTCOMDLL.dll                                        : 2.0.0.79
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.6
  RtkCoInst.dll                                       : 1.0.1.9
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5490
  RAVCpl64.exe                                        : 1.0.0.96
  RtkAPO64.dll                                        : 11.0.6000.45
  RtPgEx64.dll                                        : 6.0.6000.30
  RTCOMDLL.dll                                        : 2.0.0.79
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.6
  RCoInst64.dll                                       : 1.0.1.9
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.2
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.47
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.78
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.
        
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5485
  WDM driver for Winx64                               : 5.10.0.5485
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.6.0
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.20
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5485
  RtHDVCpl.exe                                        : 1.0.0.92
  RtkAPO.dll                                          : 11.0.6000.45
  RtkPgExt.dll                                        : 6.0.6000.29
  RTCOMDLL.dll                                        : 2.0.0.79
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.6
  RtkCoInst.dll                                       : 1.0.1.8
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5485
  RAVCpl64.exe                                        : 1.0.0.92
  RtkAPO64.dll                                        : 11.0.6000.45
  RtPgEx64.dll                                        : 6.0.6000.29
  RTCOMDLL.dll                                        : 2.0.0.79
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.6
  RCoInst64.dll                                       : 1.0.1.8
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.2
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.45
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.77
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.
        2.) Uninstall procedure for checking Rtlupd.exe file .
     
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5480
  WDM driver for Winx64                               : 5.10.0.5480
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.5.7
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.20
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5480
  RtHDVCpl.exe                                        : 1.0.0.90
  RtkAPO.dll                                          : 11.0.6000.45
  RtkPgExt.dll                                        : 6.0.6000.29
  RTCOMDLL.dll                                        : 2.0.0.79
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.6
  RtkCoInst.dll                                       : 1.0.1.7
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5480
  RAVCpl64.exe                                        : 1.0.0.90
  RtkAPO64.dll                                        : 11.0.6000.45
  RtPgEx64.dll                                        : 6.0.6000.29
  RTCOMDLL.dll                                        : 2.0.0.79
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.6
  RCoInst64.dll                                       : 1.0.1.7
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.2
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.45
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.76
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
        2.) Installer package language wrong for Japanese translation . ( Upgrade operation for Vista )
      
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5477
  WDM driver for Winx64                               : 5.10.0.5477
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.5.5
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.20
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5477
  RtHDVCpl.exe                                        : 1.0.0.89
  RtkAPO.dll                                          : 11.0.6000.45
  RtkPgExt.dll                                        : 6.0.6000.29
  RTCOMDLL.dll                                        : 2.0.0.79
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.6
  RtkCoInst.dll                                       : 1.0.1.7
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5477
  RAVCpl64.exe                                        : 1.0.0.89
  RtkAPO64.dll                                        : 11.0.6000.45
  RtPgEx64.dll                                        : 6.0.6000.29
  RTCOMDLL.dll                                        : 2.0.0.79
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.6
  RCoInst64.dll                                       : 1.0.1.7
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.2
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.44
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.75
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5473
  WDM driver for Winx64                               : 5.10.0.5473
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.5.2
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.20
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5473
  RtHDVCpl.exe                                        : 1.0.0.88
  RtkAPO.dll                                          : 11.0.6000.44
  RtkPgExt.dll                                        : 6.0.6000.29
  RTCOMDLL.dll                                        : 2.0.0.79
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.6
  RtkCoInst.dll                                       : 1.0.1.7
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5473
  RAVCpl64.exe                                        : 1.0.0.88
  RtkAPO64.dll                                        : 11.0.6000.44
  RtPgEx64.dll                                        : 6.0.6000.29
  RTCOMDLL.dll                                        : 2.0.0.79
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.6
  RtkCoInst.dll                                       : 1.0.1.7
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.2
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.42
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.74
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5470
  WDM driver for Winx64                               : 5.10.0.5470
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.5.2
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.20
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5470
  RtHDVCpl.exe                                        : 1.0.0.87
  RtkAPO.dll                                          : 11.0.6000.44
  RtkPgExt.dll                                        : 6.0.6000.28
  RTCOMDLL.dll                                        : 2.0.0.79
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.6
  RtkCoInst.dll                                       : 1.0.1.7
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5470
  RAVCpl64.exe                                        : 1.0.0.87
  RtkAPO64.dll                                        : 11.0.6000.44
  RtPgEx64.dll                                        : 6.0.6000.28
  RTCOMDLL.dll                                        : 2.0.0.79
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.6
  RtkCoInst.dll                                       : 1.0.1.7
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.2
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.40
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.73
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5464
  WDM driver for Winx64                               : 5.10.0.5464
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.4.9
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.20
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5464
  RtHDVCpl.exe                                        : 1.0.0.84
  RtkAPO.dll                                          : 11.0.6000.43
  RtkPgExt.dll                                        : 6.0.6000.27
  RTCOMDLL.dll                                        : 2.0.0.76
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.6
  RtkCoInst.dll                                       : 1.0.1.7
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.3.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5464
  RAVCpl64.exe                                        : 1.0.0.84
  RtkAPO64.dll                                        : 11.0.6000.43
  RtPgEx64.dll                                        : 6.0.6000.27
  RTCOMDLL.dll                                        : 2.0.0.76
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.6
  RtkCoInst.dll                                       : 1.0.1.7
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.3.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.2
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.38
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.72
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5449
  WDM driver for Winx64                               : 5.10.0.5449
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.4.2
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.19
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5449
  RtHDVCpl.exe                                        : 1.0.0.73
  RtkAPO.dll                                          : 11.0.6000.41
  RtkPgExt.dll                                        : 6.0.6000.27
  RTCOMDLL.dll                                        : 2.0.0.76
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.6
  RtkCoInst.dll                                       : 1.0.1.7
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.2.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5449
  RAVCpl64.exe                                        : 1.0.0.73
  RtkAPO64.dll                                        : 11.0.6000.41
  RtPgEx64.dll                                        : 6.0.6000.27
  RTCOMDLL.dll                                        : 2.0.0.76
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.6
  RtkCoInst.dll                                       : 1.0.1.7
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.2.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.2
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.36
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.71
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  WDM driver for Win2000/WinXP                        : 5.10.0.5443
  WDM driver for Winx64                               : 5.10.0.5443
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.4.2
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.19
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5443
  RtHDVCpl.exe                                        : 1.0.0.73
  RtkAPO.dll                                          : 11.0.6000.40
  RtkPgExt.dll                                        : 6.0.6000.27
  RTCOMDLL.dll                                        : 2.0.0.74
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.6
  RtkCoInst.dll                                       : 1.0.1.7
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.2.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5443
  RAVCpl64.exe                                        : 1.0.0.73
  RtkAPO64.dll                                        : 11.0.6000.40
  RtPgEx64.dll                                        : 6.0.6000.27
  RTCOMDLL.dll                                        : 2.0.0.74
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.6
  RtkCoInst.dll                                       : 1.0.1.7
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.2.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.2
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.36
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.70
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262,ALC267, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  WDM driver for Win2000/WinXP                        : 5.10.0.5436
  WDM driver for Winx64                               : 5.10.0.5436
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.3.9
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.19
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5436
  RtHDVCpl.exe                                        : 1.0.0.69
  RtkAPO.dll                                          : 11.0.6000.38
  RtkPgExt.dll                                        : 6.0.6000.27
  RTCOMDLL.dll                                        : 2.0.0.74
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.5
  RtkCoInst.dll                                       : 1.0.1.5
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.2.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5436
  RAVCpl64.exe                                        : 1.0.0.69
  RtkAPO64.dll                                        : 11.0.6000.38
  RtPgEx64.dll                                        : 6.0.6000.27
  RTCOMDLL.dll                                        : 2.0.0.74
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.5
  RtkCoInst.dll                                       : 1.0.1.5
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.2.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.2
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.35
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.69
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  WDM driver for Win2000/WinXP                        : 5.10.0.5433
  WDM driver for Winx64                               : 5.10.0.5433
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.3.6
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.17
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5433
  RtHDVCpl.exe                                        : 1.0.0.68
  RtkAPO.dll                                          : 11.0.6000.38
  RtkPgExt.dll                                        : 6.0.6000.27
  RTCOMDLL.dll                                        : 2.0.0.74
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.5
  RtkCoInst.dll                                       : 1.0.1.5
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.2.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.4.0
  RtkApoApi.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5433
  RAVCpl64.exe                                        : 1.0.0.68
  RtkAPO64.dll                                        : 11.0.6000.38
  RtPgEx64.dll                                        : 6.0.6000.27
  RTCOMDLL.dll                                        : 2.0.0.74
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.5
  RtkCoInst.dll                                       : 1.0.1.5
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.2.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.4.0
  RtkApi64.dll                                        : 1.0.0.2
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.34
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.68
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  WDM driver for Win2000/WinXP                        : 5.10.0.5413
  WDM driver for Winx64                               : 5.10.0.5413
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.3.2
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.12
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5413
  RtHDVCpl.exe                                        : 1.0.0.60
  RtkAPO.dll                                          : 11.0.6000.37
  RtkPgExt.dll                                        : 6.0.6000.25
  RTCOMDLL.dll                                        : 2.0.0.73
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.5
  RtkCoInst.dll                                       : 1.0.1.2
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.2.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.3.0
  RtkApoApi.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5413
  RAVCpl64.exe                                        : 1.0.0.60
  RtkAPO64.dll                                        : 11.0.6000.37
  RtPgEx64.dll                                        : 6.0.6000.25
  RTCOMDLL.dll                                        : 2.0.0.73
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.5
  RtkCoInst.dll                                       : 1.0.1.2
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.2.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.3.0
  RtkApi64.dll                                        : 1.0.0.2
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5413
  RtkHDM64.dll                                        : 6.0.6000.37
  RHDMEx64.dll                                        : 6.0.6000.25
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5413
  RtkHDMI.dll                                         : 6.0.6000.37
  RHDMIExt.dll                                        : 6.0.6000.25
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5413
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5413

  Driver Setup Program                                : 2.33
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.67
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  WDM driver for Win2000/WinXP                        : 5.10.0.5413
  WDM driver for Winx64                               : 5.10.0.5413
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.3.2
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.12
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5413
  RtHDVCpl.exe                                        : 1.0.0.60
  RtkAPO.dll                                          : 11.0.6000.37
  RtkPgExt.dll                                        : 6.0.6000.25
  RTCOMDLL.dll                                        : 2.0.0.73
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.5
  RtkCoInst.dll                                       : 1.0.1.2
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.2.0
  SRSHP360.dll                                        : 1.0.1.0
  SRSTSHD.dll                                         : 1.1.3.0
  RtkApoApi.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5413
  RAVCpl64.exe                                        : 1.0.0.60
  RtkAPO64.dll                                        : 11.0.6000.37
  RtPgEx64.dll                                        : 6.0.6000.25
  RTCOMDLL.dll                                        : 2.0.0.73
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.5
  RtkCoInst.dll                                       : 1.0.1.2
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.2.0
  SRSHP64.dll                                         : 1.0.1.0
  SRSTSH64.dll                                        : 1.1.3.0
  RtkApi64.dll                                        : 1.0.0.2
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5368
  RtkHDM64.dll                                        : 6.0.6000.26
  RHDMEx64.dll                                        : 6.0.6000.20
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5368
  RtkHDMI.dll                                         : 6.0.6000.26
  RHDMIExt.dll                                        : 6.0.6000.20
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5368
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5368

  Driver Setup Program                                : 2.32
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.66
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  WDM driver for Win2000/WinXP                        : 5.10.0.5404
  WDM driver for Winx64                               : 5.10.0.5404
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.3.2
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.11
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5404
  RtHDVCpl.exe                                        : 1.0.0.54
  RtkAPO.dll                                          : 11.0.6000.35
  RtkPgExt.dll                                        : 6.0.6000.24
  RTCOMDLL.dll                                        : 2.0.0.72
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.5
  RtkCoInst.dll                                       : 1.0.1.1
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.1.2.0
  SRSHP360.dll                                        : 1.0.0.0
  SRSTSHD.dll                                         : 1.1.2.0
  Vista driver for x64                                : 6.0.1.5404
  RAVCpl64.exe                                        : 1.0.0.54
  RtkAPO64.dll                                        : 11.0.6000.35
  RtPgEx64.dll                                        : 6.0.6000.24
  RTCOMDLL.dll                                        : 2.0.0.72
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.5
  RtkCoInst.dll                                       : 1.0.1.1
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.1.2.0
  SRSHP64.dll                                         : 1.0.0.0
  SRSTSH64.dll                                        : 1.1.2.0
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5368
  RtkHDM64.dll                                        : 6.0.6000.26
  RHDMEx64.dll                                        : 6.0.6000.20
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5368
  RtkHDMI.dll                                         : 6.0.6000.26
  RHDMIExt.dll                                        : 6.0.6000.20
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5368
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5368

  Driver Setup Program                                : 2.32
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.65
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  WDM driver for Win2000/WinXP                        : 5.10.0.5397
  WDM driver for Winx64                               : 5.10.0.5397
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.3.0
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.9
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5397
  RtHDVCpl.exe                                        : 1.0.0.50
  RtkAPO.dll                                          : 11.0.6000.32
  RtkPgExt.dll                                        : 6.0.6000.22
  RTCOMDLL.dll                                        : 2.0.0.70
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.5
  RtkCoInst.dll                                       : 1.0.1.1
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.0.6.0
  Vista driver for x64                                : 6.0.1.5397
  RAVCpl64.exe                                        : 1.0.0.50
  RtkAPO64.dll                                        : 11.0.6000.32
  RtPgEx64.dll                                        : 6.0.6000.22
  RTCOMDLL.dll                                        : 2.0.0.70
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.5
  RtkCoInst.dll                                       : 1.0.1.1
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.0.6.0
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5368
  RtkHDM64.dll                                        : 6.0.6000.26
  RHDMEx64.dll                                        : 6.0.6000.20
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5368
  RtkHDMI.dll                                         : 6.0.6000.26
  RHDMIExt.dll                                        : 6.0.6000.20
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5368
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5368

  Driver Setup Program                                : 2.31
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.64
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  WDM driver for Win2000/WinXP                        : 5.10.0.5391
  WDM driver for Winx64                               : 5.10.0.5391
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.65
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.2.9
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 2.0.1.7
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5391
  RtHDVCpl.exe                                        : 1.0.0.46
  RtkAPO.dll                                          : 11.0.6000.31
  RtkPgExt.dll                                        : 6.0.6000.22
  RTCOMDLL.dll                                        : 2.0.0.69
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.5
  RtkCoInst.dll                                       : 1.0.0.12
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.0.6.0
  Vista driver for x64                                : 6.0.1.5391
  RAVCpl64.exe                                        : 1.0.0.46
  RtkAPO64.dll                                        : 11.0.6000.31
  RtPgEx64.dll                                        : 6.0.6000.22
  RTCOMDLL.dll                                        : 2.0.0.69
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.5
  RtkCoInst.dll                                       : 1.0.0.12
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.0.6.0
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5368
  RtkHDM64.dll                                        : 6.0.6000.26
  RHDMEx64.dll                                        : 6.0.6000.20
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5368
  RtkHDMI.dll                                         : 6.0.6000.26
  RHDMIExt.dll                                        : 6.0.6000.20
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5368
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5368

  Driver Setup Program                                : 2.30
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.63
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  WDM driver for Win2000/WinXP                        : 5.10.0.5377
  WDM driver for Winx64                               : 5.10.0.5377
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.2.4
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5386
  RtHDVCpl.exe                                        : 1.0.0.43
  RtkAPO.dll                                          : 11.0.6000.29
  RtkPgExt.dll                                        : 6.0.6000.22
  RTCOMDLL.dll                                        : 2.0.0.69
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.0.9
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.0.6.0
  Vista driver for x64                                : 6.0.1.5386
  RAVCpl64.exe                                        : 1.0.0.43
  RtkAPO64.dll                                        : 11.0.6000.29
  RtPgEx64.dll                                        : 6.0.6000.22
  RTCOMDLL.dll                                        : 2.0.0.69
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.0.9
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.0.6.0
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5368
  RtkHDM64.dll                                        : 6.0.6000.26
  RHDMEx64.dll                                        : 6.0.6000.20
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5368
  RtkHDMI.dll                                         : 6.0.6000.26
  RHDMIExt.dll                                        : 6.0.6000.20
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5368
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5368

  Driver Setup Program                                : 2.30
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.62
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  WDM driver for Win2000/WinXP                        : 5.10.0.5377
  WDM driver for Winx64                               : 5.10.0.5377
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.2.4
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5384
  RtHDVCpl.exe                                        : 1.0.0.41
  RtkAPO.dll                                          : 11.0.6000.28
  RtkPgExt.dll                                        : 6.0.6000.21
  RTCOMDLL.dll                                        : 2.0.0.69
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSndMgr.cpl                                        : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.0.9
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.0.6.0
  Vista driver for x64                                : 6.0.1.5384
  RAVCpl64.exe                                        : 1.0.0.41
  RtkAPO64.dll                                        : 11.0.6000.28
  RtPgEx64.dll                                        : 6.0.6000.21
  RTCOMDLL.dll                                        : 2.0.0.69
  RtlCPAPI.dll                                        : 1.0.1.6
  RTSnMg64.cpl                                        : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.0.9
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.0.6.0
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5368
  RtkHDM64.dll                                        : 6.0.6000.26
  RHDMEx64.dll                                        : 6.0.6000.20
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5368
  RtkHDMI.dll                                         : 6.0.6000.26
  RHDMIExt.dll                                        : 6.0.6000.20
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5368
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5368

  Driver Setup Program                                : 2.30
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.61
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  WDM driver for Win2000/WinXP                        : 5.10.0.5377
  WDM driver for Winx64                               : 5.10.0.5377
  Realtek Soundman                                    : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.2.4
  Alcwzrd.exe                                         : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5377
  RtHDVCpl.exe                                        : 1.0.0.38
  RtkAPO.dll                                          : 11.0.6000.26
  RtkPgExt.dll                                        : 6.0.6000.20
  RTCOMDLL.dll                                        : 2.0.0.68
  RtlCPAPI.dll                                        : 1.0.1.5
  RTSndMgr.cpl                                        : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.0.7
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.0.6.0
  Vista driver for x64                                : 6.0.1.5377
  RAVCpl64.exe                                        : 1.0.0.38
  RtkAPO64.dll                                        : 11.0.6000.26
  RtPgEx64.dll                                        : 6.0.6000.20
  RTCOMDLL.dll                                        : 2.0.0.68
  RtlCPAPI.dll                                        : 1.0.1.5
  RTSnMg64.cpl                                        : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.0.7
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.0.6.0
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5356
  RtkHDM64.dll                                        : 6.0.6000.20
  RHDMEx64.dll                                        : 6.0.6000.17
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5356
  RtkHDMI.dll                                         : 6.0.6000.20
  RHDMIExt.dll                                        : 6.0.6000.17
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5356
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5356

  Driver Setup Program                                : 2.30
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.60
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  WDM driver for Win2000/WinXP                        : 5.10.0.5366
  WDM driver for Winx64                               : 5.10.0.5366
  Realtek Soundman			   	      : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.2.0
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5374
  RtHDVCpl.exe                                        : 1.0.0.36
  RtkAPO.dll                                          : 11.0.6000.25
  RtkPgExt.dll                                        : 6.0.6000.20
  RTCOMDLL.dll                                        : 2.0.0.66
  RtlCPAPI.dll                                        : 1.0.1.5
  RTSndMgr.cpl                                        : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.0.7
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.0.6.0
  Vista driver for x64                                : 6.0.1.5374
  RAVCpl64.exe                                        : 1.0.0.36
  RtkAPO64.dll                                        : 11.0.6000.25
  RtPgEx64.dll                                        : 6.0.6000.20
  RTCOMDLL.dll                                        : 2.0.0.65
  RtlCPAPI.dll                                        : 1.0.1.5
  RTSnMg64.cpl                                        : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.0.7
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.0.6.0
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5356
  RtkHDM64.dll                                        : 6.0.6000.20
  RHDMEx64.dll                                        : 6.0.6000.17
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5356
  RtkHDMI.dll                                         : 6.0.6000.20
  RHDMIExt.dll                                        : 6.0.6000.17
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5356
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5356

  Driver Setup Program                                : 2.28
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.59
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  WDM driver for Win2000/WinXP                        : 5.10.0.5366
  WDM driver for Winx64                               : 5.10.0.5366
  Realtek Soundman			   	      : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.2.0
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5372
  RtHDVCpl.exe                                        : 1.0.0.33
  RtkAPO.dll                                          : 11.0.6000.25
  RtkPgExt.dll                                        : 6.0.6000.20
  RTCOMDLL.dll                                        : 2.0.0.66
  RtlCPAPI.dll                                        : 1.0.1.5
  RTSndMgr.cpl                                        : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.0.7
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.0.6.0
  Vista driver for x64                                : 6.0.1.5372
  RAVCpl64.exe                                        : 1.0.0.33
  RtkAPO64.dll                                        : 11.0.6000.25
  RtPgEx64.dll                                        : 6.0.6000.20
  RTCOMDLL.dll                                        : 2.0.0.65
  RtlCPAPI.dll                                        : 1.0.1.5
  RTSnMg64.cpl                                        : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.0.7
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.0.6.0
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5356
  RtkHDM64.dll                                        : 6.0.6000.20
  RHDMEx64.dll                                        : 6.0.6000.17
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5356
  RtkHDMI.dll                                         : 6.0.6000.20
  RHDMIExt.dll                                        : 6.0.6000.17
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5356
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5356

  Driver Setup Program                                : 2.28
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.58
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  WDM driver for Win2000/WinXP                        : 5.10.0.5366
  WDM driver for Winx64                               : 5.10.0.5366
  Realtek Soundman			   	      : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.2.0
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5371
  RtHDVCpl.exe                                        : 1.0.0.32
  RtkAPO.dll                                          : 11.0.6000.25
  RtkPgExt.dll                                        : 6.0.6000.20
  RTCOMDLL.dll                                        : 2.0.0.66
  RtlCPAPI.dll                                        : 1.0.1.5
  RTSndMgr.cpl                                        : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.0.7
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.0.6.0
  Vista driver for x64                                : 6.0.1.5371
  RAVCpl64.exe                                        : 1.0.0.32
  RtkAPO64.dll                                        : 11.0.6000.25
  RtPgEx64.dll                                        : 6.0.6000.20
  RTCOMDLL.dll                                        : 2.0.0.65
  RtlCPAPI.dll                                        : 1.0.1.5
  RTSnMg64.cpl                                        : 1.0.0.4
  RtkCoInst.dll                                       : 1.0.0.7
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.0.6.0
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5356
  RtkHDM64.dll                                        : 6.0.6000.20
  RHDMEx64.dll                                        : 6.0.6000.17
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5356
  RtkHDMI.dll                                         : 6.0.6000.20
  RHDMIExt.dll                                        : 6.0.6000.17
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5356
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5356

  Driver Setup Program                                : 2.28
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.57
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. HDMI Device WHQL Support: ATI HDMI Devices
    4. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    5. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    6. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
Windows 2000/XP : -----------------------------------------------------
  WDM driver for Win2000/WinXP                        : 5.10.0.5366
  WDM driver for Winx64                               : 5.10.0.5366
  Realtek Soundman			   	      : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.2.0
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
Vista driver : --------------------------------------------------------
  Vista driver for x86                                : 6.0.1.5361
  RtHDVCpl.exe                                        : 1.0.0.27
  RtkAPO.dll                                          : 11.0.6000.20
  RtkPgExt.dll                                        : 6.0.6000.17
  RTCOMDLL.dll                                        : 2.0.0.65
  RtlCPAPI.dll                                        : 1.0.1.5
  RTSndMgr.cpl                                        : 1.0.0.1
  RtkCoInst.dll                                       : 1.0.0.6
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.0.6.0
  Vista driver for x64                                : 6.0.1.5361
  RAVCpl64.exe                                        : 1.0.0.27
  RtkAPO64.dll                                        : 11.0.6000.20
  RtPgEx64.dll                                        : 6.0.6000.17
  RTCOMDLL.dll                                        : 2.0.0.65
  RtlCPAPI.dll                                        : 1.0.1.5
  RTSnMg64.cpl                                        : 1.0.0.1
  RtkCoInst.dll                                       : 1.0.0.6
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.0.6.0
HDMI Driver : ---------------------------------------------------------
  Vista x64:
  RtHDMIVX.sys                                        : 6.0.1.5356
  RtkHDM64.dll                                        : 6.0.6000.20
  RHDMEx64.dll                                        : 6.0.6000.17
  Vista x86:
  RtHDMIV.sys                                         : 6.0.1.5356
  RtkHDMI.dll                                         : 6.0.6000.20
  RHDMIExt.dll                                        : 6.0.6000.17
  XP/2K x64:
  RtHDMIX.sys                                         : 5.10.0.5356
  XP/2K x86:
  RtHDMI.sys                                          : 5.10.0.5356

  Driver Setup Program                                : 2.27
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.56
    Realtek HD Audio Driver support all of Realtek HD Audio Codec in Vista/WinXP/Win2000/Win2003 .
    1. Vista WHQL Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP WHQL Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    4. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    5. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5345
  WDM driver for Winx64                               : 5.10.0.5345
  Realtek Soundman			   	      : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.1.4
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Vista driver :
  Vista driver for x86                                : 6.0.1.5361
  RtHDVCpl.exe                                        : 1.0.0.27
  RtkAPO.dll                                          : 11.0.6000.20
  RtkPgExt.dll                                        : 6.0.6000.17
  RTCOMDLL.dll                                        : 2.0.0.65
  RtlCPAPI.dll                                        : 1.0.1.5
  RTSndMgr.cpl                                        : 1.0.0.1
  RtkCoInst.dll                                       : 1.0.0.6
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.0.6.0
  Vista driver for x64                                : 6.0.1.5361
  RAVCpl64.exe                                        : 1.0.0.27
  RtkAPO64.dll                                        : 11.0.6000.20
  RtPgEx64.dll                                        : 6.0.6000.17
  RTCOMDLL.dll                                        : 2.0.0.65
  RtlCPAPI.dll                                        : 1.0.1.5
  RTSnMg64.cpl                                        : 1.0.0.1
  RtkCoInst.dll                                       : 1.0.0.6
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.0.6.0

  Driver Setup Program                                : 2.27
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.55
    1. Vista logo Codec Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP logo Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    4. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    5. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5345
  WDM driver for Winx64                               : 5.10.0.5345
  Realtek Soundman			   	      : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.1.4
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Vista driver :
  Vista driver for x86                                : 6.0.1.5350
  RtHDVCpl.exe                                        : 1.0.0.21
  RtkAPO.dll                                          : 11.0.6000.16
  RtkPgExt.dll                                        : 6.0.6000.15
  RTCOMDLL.dll                                        : 2.0.0.65
  RtlCPAPI.dll                                        : 1.0.1.5
  RTSndMgr.cpl                                        : 1.0.0.1
  RtkCoInst.dll                                       : 1.0.0.3
  SRSTSXT.dll                                         : 3.2.0.0
  SRSWOW.dll                                          : 1.0.6.0
  Vista driver for x64                                : 6.0.1.5350
  RAVCpl64.exe                                        : 1.0.0.21
  RtkAPO64.dll                                        : 11.0.6000.16
  RtPgEx64.dll                                        : 6.0.6000.15
  RTCOMDLL.dll                                        : 2.0.0.65
  RtlCPAPI.dll                                        : 1.0.1.5
  RTSnMg64.cpl                                        : 1.0.0.1
  RtkCoInst.dll                                       : 1.0.0.4
  SRSTSX64.dll                                        : 3.2.0.0
  SRSWOW64.dll                                        : 1.0.6.0

  Driver Setup Program                                : 2.24
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.54
    1. Vista logo Codec Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP logo Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    4. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    5. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        
       CPL :
        1.) Customization.
      
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5345
  WDM driver for Winx64                               : 5.10.0.5345
  Realtek Soundman			   	      : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.1.4
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Vista driver :
  Vista driver for x86                                : 6.0.1.5334
  RtHDVCpl.exe                                        : 1.0.0.11
  RtkAPO.dll                                          : 11.0.5600.13
  RtkPgExt.dll                                        : 6.0.5600.12
  RTCOMDLL.dll                                        : 1.0.0.63
  RtlCPAPI.dll                                        : 1.0.1.5
  RTSndMgr.cpl                                        : 1.0.0.1
  RtkCoInst.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5334
  RAVCpl64.exe                                        : 1.0.0.11
  RtkAPO64.dll                                        : 11.0.5600.13
  RtPgEx64.dll                                        : 6.0.5600.12
  RTCOMDLL.dll                                        : 1.0.0.63
  RtlCPAPI.dll                                        : 1.0.1.5
  RTSnMg64.cpl                                        : 1.0.0.1
  RtkCoInst.dll                                       : 1.0.0.2

  Driver Setup Program                                : 2.23
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.53
    1. Vista logo Codec Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP logo Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    4. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    5. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        2.) Fixed issue -> DTM Test \ Hal timer issue for V5331 Vista driver ( Potential risk ).

       CPL :
        1.) Customization.
      
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5324
  WDM driver for Winx64                               : 5.10.0.5324
  Realtek Soundman			   	      : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.1.1
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Vista driver :
  Vista driver for x86                                : 6.0.1.5334
  RtHDVCpl.exe                                        : 1.0.0.11
  RtkAPO.dll                                          : 11.0.5600.13
  RtkPgExt.dll                                        : 6.0.5600.12
  RTCOMDLL.dll                                        : 1.0.0.63
  RtlCPAPI.dll                                        : 1.0.1.5
  RTSndMgr.cpl                                        : 1.0.0.1
  RtkCoInst.dll                                       : 1.0.0.2
  Vista driver for x64                                : 6.0.1.5334
  RAVCpl64.exe                                        : 1.0.0.11
  RtkAPO64.dll                                        : 11.0.5600.13
  RtPgEx64.dll                                        : 6.0.5600.12
  RTCOMDLL.dll                                        : 1.0.0.63
  RtlCPAPI.dll                                        : 1.0.1.5
  RTSnMg64.cpl                                        : 1.0.0.1
  RtkCoInst.dll                                       : 1.0.0.2

  Driver Setup Program                                : 2.21
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.52
    1. Vista logo Codec Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP logo Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    4. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    5. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        2.) Known issue -> DTM Test \ Hal timer issue for V5331 Vista driver ( Potential risk ).

       CPL :
        1.) Customization.
      
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5324
  WDM driver for Winx64                               : 5.10.0.5324
  Realtek Soundman			   	      : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.1.1
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Vista driver :
  Vista driver for x86                                : 6.0.1.5331
  RtHDVCpl.exe                                        : 1.0.0.9
  RtkAPO.dll                                          : 11.0.5600.13
  RtkPgExt.dll                                        : 6.0.5600.12
  RTCOMDLL.dll                                        : 1.0.0.63
  RtlCPAPI.dll                                        : 1.0.0.7
  RTSndMgr.cpl                                        : 1.0.0.1
  RtkCoInst.dll                                       : 1.0.0.1
  Vista driver for x64                                : 6.0.1.5331
  RAVCpl64.exe                                        : 1.0.0.9
  RtkAPO64.dll                                        : 11.0.5600.13
  RtPgEx64.dll                                        : 6.0.5600.12
  RTCOMDLL.dll                                        : 1.0.0.63
  RtlCPAPI.dll                                        : 1.0.0.7
  RTSnMg64.cpl                                        : 1.0.0.1
  RtkCoInst.dll                                       : 1.0.0.1

  Driver Setup Program                                : 2.20
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.51
    1. Vista logo Codec Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP logo Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC267,ALC268
    3. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    4. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    5. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .

       CPL :
        1.) Customization.
      
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5324
  WDM driver for Winx64                               : 5.10.0.5324
  Realtek Soundman			   	      : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.1.1
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Vista driver :
  Vista driver for x86                                : 6.0.1.5322
  RtHDVCpl.exe                                        : 1.0.0.7
  RtkAPO.dll                                          : 11.0.5600.13
  RtkPgExt.dll                                        : 6.0.5600.12
  RTCOMDLL.dll                                        : 1.0.0.63
  RtlCPAPI.dll                                        : 1.0.0.7
  RTSndMgr.cpl                                        : 1.0.0.1
  Vista driver for x64                                : 6.0.1.5322
  RAVCpl64.exe                                        : 1.0.0.7
  RtkAPO64.dll                                        : 11.0.5600.13
  RtPgEx64.dll                                        : 6.0.5600.12
  RTCOMDLL.dll                                        : 1.0.0.63
  RtlCPAPI.dll                                        : 1.0.0.7
  RTSnMg64.cpl                                        : 1.0.0.1
  Driver Setup Program                                : 2.20
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.50
    1. Vista logo Codec Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP logo Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    3. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    4. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    5. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .

       CPL :
        1.) Customization.
      
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5319
  WDM driver for Winx64                               : 5.10.0.5319
  Realtek Soundman			   	      : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.0.8
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Vista driver :
  Vista driver for x86                                : 6.0.1.5322
  RtHDVCpl.exe                                        : 1.0.0.7
  RtkAPO.dll                                          : 11.0.5600.13
  RtkPgExt.dll                                        : 6.0.5600.12
  RTCOMDLL.dll                                        : 1.0.0.63
  RtlCPAPI.dll                                        : 1.0.0.7
  RTSndMgr.cpl                                        : 1.0.0.1
  Vista driver for x64                                : 6.0.1.5322
  RAVCpl64.exe                                        : 1.0.0.7
  RtkAPO64.dll                                        : 11.0.5600.13
  RtPgEx64.dll                                        : 6.0.5600.12
  RTCOMDLL.dll                                        : 1.0.0.63
  RtlCPAPI.dll                                        : 1.0.0.7
  RTSnMg64.cpl                                        : 1.0.0.1
  Driver Setup Program                                : 2.19
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.49
    1. Vista logo Codec Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. Windows 2000/XP logo Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861VC, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    3. OS Supporting: Microsoft WindowsXP, Widnows2000, Vista x86/x64
    4. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    5. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .

       CPL :
        1.) Customization.
      
  Windows 2000/XP :
  WDM driver for Win2000/WinXP                        : 5.10.0.5319
  WDM driver for Winx64                               : 5.10.0.5319
  Realtek Soundman			   	      : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.1.0.8
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Vista driver :
  Vista driver for x86                                : 6.0.1.5317
  RtHDVCpl.exe                                        : 1.0.0.6
  RtkAPO.dll                                          : 11.0.5600.12
  RtkPgExt.dll                                        : 6.0.5600.12
  RTCOMDLL.dll                                        : 1.0.0.63
  RtlCPAPI.dll                                        : 1.0.0.7
  RTSndMgr.cpl                                        : 1.0.0.1
  Vista driver for x64                                : 6.0.1.5317
  RAVCpl64.exe                                        : 1.0.0.6
  RtkAPO64.dll                                        : 11.0.5600.12
  RtPgEx64.dll                                        : 6.0.5600.12
  RTCOMDLL.dll                                        : 1.0.0.63
  RtlCPAPI.dll                                        : 1.0.0.7
  RTSnMg64.cpl                                        : 1.0.0.1
  Driver Setup Program                                : 2.19
  
  Windows 2000/XP Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.48
  Vista driver Version: 5.10.0.5317
    1. Vista logo Codec Supporting: ALC882, ALC883, ALC885, ALC888, ALC861VD, ALC660, ALC662, ALC260, ALC262, ALC268
    2. OS Supporting: Microsoft Windows Vista x86/x64
    
  Vista driver for x86                                : 6.10.0.5317
  RtHDVCpl.exe                                        : 1.0.0.6
  RtkAPO.dll                                          : 11.0.5600.12
  RtkPgExt.dll                                        : 6.0.5600.12
  RTCOMDLL.dll                                        : 1.0.0.63
  RtlCPAPI.dll                                        : 1.0.0.7
  RTSndMgr.cpl                                        : 1.0.0.1
  Vista driver for x64                                : 6.10.0.5317
  RAVCpl64.exe                                        : 1.0.0.6
  RtkAPO64.dll                                        : 11.0.5600.12
  RtPgEx64.dll                                        : 6.0.5600.12
  RTCOMDLL.dll                                        : 1.0.0.63
  RtlCPAPI.dll                                        : 1.0.0.7
  RTSnMg64.cpl                                        : 1.0.0.1
  Driver Setup Program                                : 2.19
//=================
Driver Package R1.47
  RtkHDAud.sys Version: 5.10.0.5296
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861, ALC861VD, ALC660, ALC260, ALC262, ALC268
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .

       CPL :
        1.) Customization.
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5296
  WDM driver for Winx64                               : 5.10.0.5296
  Realtek Soundman			   	      : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.9.8
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Driver Setup Program                                : 2.18
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.46
  RtkHDAud.sys Version: 5.10.0.5294
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861, ALC861VD, ALC660, ALC260, ALC262, ALC268
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .

       CPL :
        1.) Customization.
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5294
  WDM driver for Winx64                               : 5.10.0.5294
  Realtek Soundman			   	      : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.9.6
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Driver Setup Program                                : 2.16
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.45
  RtkHDAud.sys Version: 5.10.0.5288
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861, ALC861VD, ALC660, ALC260, ALC262, ALC268
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .

       CPL :
        1.) Customization.
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5288
  WDM driver for Winx64                               : 5.10.0.5288
  Realtek Soundman			   	      : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.9
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.9.1
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Driver Setup Program                                : 2.15
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.44
  RtkHDAud.sys Version: 5.10.0.5286
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861, ALC861VD, ALC660, ALC260, ALC262, ALC268
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .

       CPL :
        1.) Customization.
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5286
  WDM driver for Winx64                               : 5.10.0.5286
  Realtek Soundman			   	      : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.8
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.8.7
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Driver Setup Program                                : 2.15
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.43
  RtkHDAud.sys Version: 5.10.0.5283
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861, ALC861VD, ALC660, ALC260, ALC262, ALC268
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .

       CPL :
        1.) Customization.
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5283
  WDM driver for Winx64                               : 5.10.0.5283
  Realtek Soundman			   	      : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.8
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.8.3
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Driver Setup Program                                : 2.15
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.42
  RtkHDAud.sys Version: 5.10.0.5282
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861, ALC861VD, ALC660, ALC260, ALC262, ALC268
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        2.) Fix some game issue .

       CPL :
        1.) Customization.
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5282
  WDM driver for Winx64                               : 5.10.0.5282
  Realtek Soundman			   	      : 1.0.0.30
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.8
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.8.0
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Driver Setup Program                                : 2.15
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.41
  RtkHDAud.sys Version: 5.10.0.5273
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861, ALC861VD, ALC660, ALC260, ALC262, ALC268
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization.  

       CPL :
        1.) Customization.
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5273
  WDM driver for Winx64                               : 5.10.0.5273
  Realtek Soundman			   	      : 1.0.0.29
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.8
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.7.3
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Driver Setup Program                                : 2.14
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.40
  RtkHDAud.sys Version: 5.10.0.5268
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861, ALC861VD, ALC660, ALC260, ALC262, ALC268
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .

       CPL :
        1.) Customization.
                 
       InstallShield package :
        1.) Correct present driver version in "Add or Remove Programs \ Support Information" .
        2.) Windows 2000 installation reboot twice problem .
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5268
  WDM driver for Winx64                               : 5.10.0.5268
  Realtek Soundman			   	      : 1.0.0.29
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.8
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.7.0
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Driver Setup Program                                : 2.14
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.39
  RtkHDAud.sys Version: 5.10.0.5265
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861, ALC861VD,ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .

       CPL :
        1.) Customization.
        2.) Add support for left panel and right panel config.
         
       InstallShield package :
        1.) Copy file rule in Vista system .
        2.) Show driver version in "Add or Remove Programs \ Support Information" .
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5265
  WDM driver for Winx64                               : 5.10.0.5265
  Realtek Soundman			   	      : 1.0.0.29
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.8
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.6.9
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Driver Setup Program                                : 2.13
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.38
  RtkHDAud.sys Version: 5.10.0.5257
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .

       CPL :
        1.) Customization.
         
       InstallShield package :
        1.) Add "XP2K" and "Vista" folder name for installation .
        2.) Abort flag setting .
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5257
  WDM driver for Winx64                               : 5.10.0.5257
  Realtek Soundman			   	      : 1.0.0.29
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.8
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.6.6
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Driver Setup Program                                : 2.11
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.37
  RtkHDAud.sys Version: 5.10.0.5253
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .

       CPL :
        1.) Customization.
         
       InstallShield package :
        1.) Upgrade to IS11.5 .
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5253
  WDM driver for Winx64                               : 5.10.0.5253
  Realtek Soundman			   	      : 1.0.0.29
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.8
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.64
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.6.4
  Alcwzrd.exe 				              : 1.1.0.36
  SkyTel.exe                                          : 1.0.0.0
  Driver Setup Program                                : 2.09
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.36
  RtkHDAud.sys Version: 5.10.0.5247
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC888, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        2.) Add ALC888 .
       
       CPL :
        1.) Customization.
         
       InstallShield package :
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5247
  WDM driver for Winx64                               : 5.10.0.5247
  Realtek Soundman			   	      : 1.0.0.28
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.8
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.62
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.5.9
  Alcwzrd.exe 				              : 1.1.0.35
  Driver Setup Program                                : 2.06
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.35
  RtkHDAud.sys Version: 5.10.0.5242
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
       
       CPL :
        1.) Customization.
         
       InstallShield package :
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5242
  WDM driver for Winx64                               : 5.10.0.5242
  Realtek Soundman			   	      : 1.0.0.28
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.8
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.62
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.5.4
  Alcwzrd.exe 				              : 1.1.0.35
  Driver Setup Program                                : 2.06
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.34
  RtkHDAud.sys Version: 5.10.0.5233
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        2.) Fixed Adobe Premiere Pro 1.5 Crash issue .
       
       CPL :
        1.) Customization.
         
       InstallShield package :
        1.) Rtlupd termination return error code .
        2.) Receive error code rule from Rtlupd SetupAPI .
        3.) SetupCopyOEM install rule .
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5233
  WDM driver for Winx64                               : 5.10.0.5233
  Realtek Soundman			   	      : 1.0.0.28
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.8
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.62
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.4.9
  Alcwzrd.exe 				              : 1.1.0.35
  Driver Setup Program                                : 2.06
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.33
  RtkHDAud.sys Version: 5.10.0.5229
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
       
       CPL :
        1.) Customization.
         
       InstallShield package :
        1.) Bus driver detect issue .
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5229
  WDM driver for Winx64                               : 5.10.0.5229
  Realtek Soundman			   	      : 1.0.0.28
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.8
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.61
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.4.7
  Alcwzrd.exe 				              : 1.1.0.34
  Driver Setup Program                                : 2.05
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.32
  RtkHDAud.sys Version: 5.10.0.5224
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
       
       CPL :
        1.) Customization.
         
       InstallShield package :
        1.) Report installation progress and result to "C:\RTHSetup.log" within silent mode .
        2.) Rtlupd setup API will not appear message dialog in silent mode .
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5224
  WDM driver for Winx64                               : 5.10.0.5224
  Realtek Soundman			   	      : 1.0.0.28
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.8
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.61
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.4.4
  Alcwzrd.exe 				              : 1.1.0.34
  Driver Setup Program                                : 2.04
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.31
  RtkHDAud.sys Version: 5.10.0.5221
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC885, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        2.) Add ALC885 HD Audio Codec for WHQL .
       
       CPL :
        1.) Customization.
         
       InstallShield package :
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5221
  WDM driver for Winx64                               : 5.10.0.5221
  Realtek Soundman			   	      : 1.0.0.27
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.8
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.60
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.4.2
  Alcwzrd.exe 				              : 1.1.0.33
  Driver Setup Program                                : 2.03
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.30
  RtkHDAud.sys Version: 5.10.0.5211
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization .
        2.) Bug fixed when recording AEC device failed on 880 .
       
       CPL :
        1.) Customization.
         
       InstallShield package :
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5211
  WDM driver for Winx64                               : 5.10.0.5211
  Realtek Soundman			   	      : 1.0.0.24
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.8
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.58
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.3.9
  Alcwzrd.exe 				              : 1.1.0.31
  Driver Setup Program                                : 2.03
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.29
  RtkHDAud.sys Version: 5.10.0.5202
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization.
       
       CPL :
        1.) Customization.
         
       InstallShield package :
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5202
  WDM driver for Winx64                               : 5.10.0.5202
  Realtek Soundman			   	      : 1.0.0.21
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.7
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.54
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.3.4
  Alcwzrd.exe 				              : 1.1.0.29
  Driver Setup Program                                : 2.02c
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.28
  RtkHDAud.sys Version: 5.10.0.5200
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization.
        2.) Add ALC265 .
       
       CPL :
        1.) Side speaker testing has no sound when 3D engine is disabled.
         
       InstallShield package :
        1.) Add Chipset ID VEN_1002&DEV_4383 .
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5200
  WDM driver for Winx64                               : 5.10.0.5200
  Realtek Soundman			   	      : 1.0.0.21
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.7
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.53
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.3.2
  Alcwzrd.exe 				              : 1.1.0.28
  Driver Setup Program                                : 2.02c
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.27
  RtkHDAud.sys Version: 5.10.0.5188
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization.
         
       InstallShield package :
           Fix :
             1. Add installation file "RTHDAEQ*.dat" .
             2. Add Package version in setup.ini .
             3. Manual installation setting for InstallShield .
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5188
  WDM driver for Winx64                               : 5.10.0.5188
  Realtek Soundman			   	      : 1.0.0.21
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.7
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.53
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.2.6
  Alcwzrd.exe 				              : 1.1.0.28
  Driver Setup Program                                : 2.02a
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.26
  RtkHDAud.sys Version: 5.10.0.5178
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization.
         
       InstallShield package :
           Fix :
             1. Set rebooting twice for installation UAA QFE on Win2000 .
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5178
  WDM driver for Winx64                               : 5.10.0.5178
  Realtek Soundman			   	      : 1.0.0.21
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.6
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.52
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.2.1
  Alcwzrd.exe 				              : 1.1.0.28
  Driver Setup Program                                : 2.00
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.25
  RtkHDAud.sys Version: 5.10.0.5172
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization.
         
       InstallShield package :
           Fix :
             1. Rtlupd.exe(2.5.0.5) fixed roll-back problem ( It can not delete oem.inf file before update driver ).
             2. Change Azalia name in setup.ini file .
             3. Don't popup Rtlupd dialog when you select "No" on Hotfix installation dialog .
           Add :
             1. System language identifier .
             2. Change pop-up dialog Product name ( Azalia->High Definition ) . 
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5172
  WDM driver for Winx64                               : 5.10.0.5172
  Realtek Soundman			   	      : 1.0.0.21
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.6
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.51
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.1.7
  Alcwzrd.exe 				              : 1.1.0.27
  Driver Setup Program                                : 1.99
 
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.24
  RtkHDAud.sys Version: 5.10.0.5152
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
         1.) Customization.
         2.) Support 192KHz sample rate output.
         
       InstallShield package :
           Fix : 
             1. Reboot timing after installation MS QFE ( UAA driver ) .
             2. Uninstallation dialog description .
           Add :
             1. MS hotfix KB901105 can be included by HD pcakage ( If get MS licence ) .
             2. Hotfix KB901105 Warning message .
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5152
  WDM driver for Winx64                               : 5.10.0.5152
  Realtek Soundman			   	      : 1.0.0.18
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.7
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.4
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.46
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.0.8
  Alcwzrd.exe 				              : 1.1.0.24
  Driver Setup Program                                : 1.96
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.23
  RtkHDAud.sys Version: 5.10.0.5136
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
         1.) Customization.
         2.) Support new codec ALC262, ALC883
         
       InstallShield package :
         1.) Check OS service pack number with InstallShield .
         2.) Change audio wizard quitting procedure .
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5136
  WDM driver for Winx64                               : 5.10.0.5136
  Realtek Soundman			   	      : 1.0.0.17
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.7
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.4
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.43
  Realtek Sound Effect Manager(RTHDCPL)               : 1.1.2.3
  Alcwzrd.exe 				              : 1.1.0.23
  Driver Setup Program                                : 1.92
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.22
  RtkHDAud.sys Version: 5.10.0.5128
    1. Codec Supporting: ALC880, ALC882, ALC861, ALC260
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
         1.) Customization.
         
       InstallShield package :
         1.) Setup progress backward .
         2.) Driver size on Add and remove programs .
         3.) Refresh driver size on Add and Remove Programs .
         4.) Check RtlExupd.dll version .
         5.) Check RtlHDCpl.exe version .
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5128
  WDM driver for Winx64                               : 5.10.0.5128
  Realtek Soundman			   	      : 1.0.0.17
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.7
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.4
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.40
  Realtek Sound Effect Manager(RTHDCPL)               : 1.1.1.9
  Alcwzrd.exe 				              : 1.1.0.20
  Driver Setup Program                                : 1.91
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.21
  RtkHDAud.sys Version: 5.10.0.5127
    1. Codec Supporting: ALC880, ALC882, ALC260
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
         1.) Customization.
         2.) Support DTS Encoder and DTS Neo for special version codec .
      
  SoundMan.exe Version: 1.0.0.17
  ALSndMgr.cpl Version: 1.0.0.7  
  Rtlcpl.exe Version: 1.0.1.40	
  Alcwzrd.exe Version: 1.1.0.20
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.20
  RtkHDAud.sys Version: 5.10.0.5125
    1. Codec Supporting: ALC880, ALC882, ALC260
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
         1.) Customization.
         2.) Fixed the issue of SPDIF-In capture
      
  SoundMan.exe Version: 1.0.0.17
  ALSndMgr.cpl Version: 1.0.0.7  
  Rtlcpl.exe Version: 1.0.1.40	
  Alcwzrd.exe Version: 1.1.0.20
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.19
  RtkHDAud.sys Version: 5.10.0.5123
    1. Codec Supporting: ALC880, ALC882, ALC260
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1. Customization.    
	2. Avoid Pop noise when toggle output sampling rate for ALC260.
	3. Restore the original timer resolution first before check the original system timer resolution.
     
       For New architecture:
         1.) Customization.
         2.) Driver store mixer setting after windows reboot
      
  SoundMan.exe Version: 1.0.0.14
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.39	
  Alcwzrd.exe Version: 1.1.0.19
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.18
  RtkHDAud.sys Version: 5.10.0.5122
    1. Codec Supporting: ALC880, ALC882, ALC260
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1. Customization.
	2.Add 2 default values of codec subsystem ID for ALC260.
      
       For New architecture:
         1.) Customization.
         2.) Fixed the issue of uncontinuous sound after suspend on some machine.
      
  SoundMan.exe Version: 1.0.0.14
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.38	
  Alcwzrd.exe Version: 1.1.0.18
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.17
  RtkHDAud.sys Version: 5.10.0.5120
    1. Codec Supporting: ALC880, ALC882, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1. Customization.
        2. Restore certain register value when resume from system suspend. 
      
       For New architecture:
         1.) Customization.
         2.) Improve reliability for switching mutiple streaming.
      
  SoundMan.exe Version: 1.0.0.14
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.38	
  Alcwzrd.exe Version: 1.1.0.18
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.16
  RtkHDAud.sys Version: 5.10.0.5119
    1. Codec Supporting: ALC880, ALC882, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
       1. Customization.
       2. Fix initial noise issue for the certain models.
       3. Check codec SubsystemID verb to decide the driver path when driver initialize.
       4. Don't modify Configuration byte Verbs when driver initialize.
       5. Fix Buffer size un-alignment issue.
       
       For New architecture:
         1.) Customization.
         2.) Fix the problem when play AC-3 stream by SPDIF interface
         3.) Change device name for mutiple streaming issue.
      
  SoundMan.exe Version: 1.0.0.14
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.38	
  Alcwzrd.exe Version: 1.1.0.17
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.15
  RtkHDAud.sys Version: 5.10.0.5116
    1. Codec Supporting: ALC880, ALC882, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio UAAV1(5011)
    4. Add/Fix
       1.) Customization.
       2.) Auto lock SPDIF-in signal when SPDIF-in signal is unlocked.
       3.) Fix SPDIF out copy protection issue.
       4.) Add patch code for ALC260 potential risk.
 
       For New architecture:
         1.) Customization.
         2.) Fix new feature problem on mutiple streaming.
         3.) Fix capture problem on ALC882.
      
  SoundMan.exe Version: 1.0.0.14
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.38	
  Alcwzrd.exe Version: 1.1.0.17
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5011
//=================
Driver Package R1.14
  RtkHDAud.sys Version: 5.10.0.5109
    1. Codec Supporting: ALC880, ALC882, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio UAAV1(5011)
    4. Add/Fix
       1.) Customization.
       2.) Reduce delay time when volume is adjusted.
       3.) Fix hang up issue when system resume from S3.
 
       For New architecture:
         1.) New architecture of HD audio driver formal release.
      
  SoundMan.exe Version: 1.0.0.14
  ALSndMgr.cpl Version: 1.0.0.4  
  Rtlcpl.exe Version: 1.0.1.37	
  Alcwzrd.exe Version: 1.1.0.16
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5011
//=================
Driver Package R1.13
  RtkHDAud.sys Version: 5.10.0.5038
    1. Codec Supporting: ALC880, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio UAAV1(5011)
    4. Add/Fix
     1) Reduce initialize noise
      
  SoundMan.exe Version: 1.0.0.14
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.36	
  Alcwzrd.exe Version: 1.1.0.15
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5011
//=================
Driver Package R1.12
  RtkHDAud.sys Version: 5.10.0.5037
    1. Codec Supporting: ALC880, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio UAAV1(5011)
    4. Add/Fix
     1) Improve recording performance.
     2) Reduce initialize noise
      
  SoundMan.exe Version: 1.0.0.14
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.36	
  Alcwzrd.exe Version: 1.1.0.15
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5011
//=================
Driver Package R1.11
  RtkHDAud.sys Version: 5.10.0.5036
    1. Codec Supporting: ALC880, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio UAAV1(5011)
    4. Add/Fix
     
  SoundMan.exe Version: 1.0.0.14
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.35	
  Alcwzrd.exe Version: 1.1.0.15
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5011
//=================
Driver Package R1.10
  RtkHDAud.sys Version: 5.10.0.5034
    1. Codec Supporting: ALC880, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio UAAV1(5011)
    4. Add/Fix
     1) Fix the problem that there is little noise when start stream playing
     2) Fix the problem that in WinDVD, the SPDIF option still exist even 
        there is no SPDIF
    
  
  SoundMan.exe Version: 1.0.0.14
   1.Set the default recording device as "Realtek HD Audio rear input" device 

  ALSndMgr.cpl Version: 1.0.0.5
  
  Rtlcpl.exe Version: 1.0.1.34
	
  Alcwzrd.exe Version: 1.1.0.15
   1.Keep previous Jack setting.
   2.Check whether have any jack plugin when restart OS,and popup the 
     device window if wizard detect any new device plugin.

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5011
//=================
Driver Package R1.09
  RtkHDAud.sys Version: 5.10.0.5033
    1. Codec Supporting: ALC880, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio OOB Binaries V1.0
     
  SoundMan.exe Version: 1.0.0.14
    1.Set the default recording device as "Realtek HD Audio rear input" device 
  	
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.33   
  Alcwzrd.exe Version: 1.1.0.14

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5010
//=================
Driver Package R1.08
  RtkHDAud.sys Version: 5.10.0.5032
    1. Codec Supporting: ALC880, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio OOB Binaries V1.0
      
  SoundMan.exe Version: 1.0.0.12 	
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.33   
  Alcwzrd.exe Version: 1.1.0.14

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5010
//=================
Driver Package R1.07
  RtkHDAud.sys Version: 5.10.0.5031
    1. Codec Supporting: ALC880, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio OOB Binaries V1.0
    4. Add/Fix
     1) Fix the probelm when playback with sound recorder, when change frequency
        from 48k to 44.1k in SPDIF page, playback will stop
     2) Support for ALC880G, ALC880D, ALC260D
     3) Fix the the problem that system will hang up while perform audio test 
        in 3DMark 2003
  
  SoundMan.exe Version: 1.0.0.12  	
  ALSndMgr.cpl Version: 1.0.0.5
  
  Rtlcpl.exe Version: 1.0.1.32
  1.Fix word collision problem in Multi-Language.
   
  Alcwzrd.exe Version: 1.1.0.13
  1.Restore previous jack setting when reboot system.

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5010
//=================
Driver Package R1.06
  RtkHDAud.sys Version: 5.10.0.5030
    1. Codec Supporting: ALC880, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio OOB Binaries V1.0
    4. Add/Fix
  
  SoundMan.exe Version: 1.0.0.12  	
  ALSndMgr.cpl Version: 1.0.0.3 
  Rtlcpl.exe Version: 1.0.1.31   
  Alcwzrd.exe Version: 1.1.0.12

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5010
//=================
Driver Package R1.05
  RtkHDAud.sys Version: 5.10.0.5029
    1. Codec Supporting: ALC880, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio OOB Binaries V1.0
    4. Add/Fix
     1) Add support for ALC861
     2) Fix the noise problem that when recording from SPDIF In at 96khz
  
  SoundMan.exe Version: 1.0.0.12  	
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.31   
  Alcwzrd.exe Version: 1.1.0.12

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5010
//=================
Driver Package R1.04
  RtkHDAud.sys Version: 5.10.0.5028
    1. Codec Supporting: ALC880, ALC260
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio OOB Binaries V1.0
    4. Add/Fix
     1) For UAJ A to A volume line, change type from KSNODETYPE_MICROPHONE 
        to KSNODETYPE_ANALOG_CONNECTOR
     2) Fix the problem that SPDIF out no sound in WinDVD
     3) Fix the problem that there is balance conrtol in Center and 
        Subwoofer volume line in W2k
     4) Change the conponent tyep of SPDIF-In from "KSNODETYPE_ANALOG_CONNECTOR" 
        to "KSNODETYPE_SPDIF_INTERFACE"
     5) Fix the problem that mute SPDIF out in mixer doesn't work
  
  SoundMan.exe Version: 1.0.0.12 	
  ALSndMgr.cpl Version: 1.0.0.3
  
  Rtlcpl.exe Version: 1.0.1.31
   1.Turn off all sound effect when speaker test!
   
  Alcwzrd.exe Version: 1.1.0.12

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5010

//=================
Driver Package R1.03
  RtkHDAud.sys Version: 5.10.0.5027
  SoundMan.exe Version: 1.0.0.4
  ALSndMgr.cpl Version: 1.0.0.2
  
  Rtlcpl.exe Version: 1.0.1.29
   1.Sync the status which Enable/Disable wizard with alcwzrd
   2.Make the tab of "Audio Wizard" independent from  menu tabs.
   3.Stop the play sound when menu tab is change.
   
  Alcwzrd.exe Version: 1.1.0.12
    1.Fixed broken wizard image.
    2.Sync the status which Enable/Disable wizard with rtlcpl.

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5010

//=================
Driver Package R1.01/R1.02
  RtkHDAud.sys Version: 5.10.0.5022
    1. Codec Supporting:
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio OOB Binaries V1.0
    4. Add/Fix
 
  SoundMan.exe Version: 1.0.0.4
  ALSndMgr.cpl Version: 1.0.0.2
  Rtlcpl.exe Version: 1.0.1.23
   
  Alcwzrd.exe Version: 1.1.0.5

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5010

//=================
Driver Package R1.0
  RtkHDAud.sys Version: 5.10.0.5017
    1. Codec Supporting: Add ALC880/ALC880M Rev.F Rev.G, ALC860
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio OOB Binaries V1.0
    4. Add/Fix
 
  SoundMan.exe Version: 1.0.0.4
  ALSndMgr.cpl Version: 1.0.0.2
  Rtlcpl.exe Version: 1.0.1.23
   
  Alcwzrd.exe Version: 1.1.0.5

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5010
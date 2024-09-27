Radar module evaluation kit
TITAN series
Start guide
Estacay Electronics Co., Ltd.
No.ST219-0007-Q01(Rev1.6)
1/11
Contents
1. Contents ................................................................................................................................................................................................................ 2
2. What you need ................................................................................................................................................................................................ 2
3. Procedure ................................................................................................................................................................................................ 2
3.1. STEP 1. Connect the module to the PC .................................................................................................................................. 2
3.2. STEP 2. Install the driver .................................................................................................................................................................. 2
3.3. STEP 3. Install the software ................................................................................................................................................................ 8
3.4. STEP 4. Start the software ................................................................................................................................................................ 8
3.5. STEP 5. Connecting to the module ................................................................................................................................................ 9
3.6. STEP 6. Loading the CFG file ................................................................................................................................................ 10
3.7. STEP 7. Measurement ................................................................................................................................................................ 10
3.8. STEP 8. Finishing ................................................................................................................................................................ 11
4. Notes ................................................................................................................................................................................................ 11
No.ST219-0007-Q01(Rev1.6)
2/11
1. Contents
2. What you need to prepare
・PC
(Supported OS) Windows 10 (Recommended specs) CPU: Intel Core i5 or higher, Memory: 8GB or more
*Other applications running in the background may affect operation.
3. Procedure
STEP 1. Connecting the module to the PC
STEP 2. Installing the driver
STEP 3. Installing the software
STEP 4. Starting the software
STEP 5. Connecting to the module
STEP 6. Loading the CFG file
STEP 7. Measurement
STEP 8. Finish
3.1. STEP 1. Connecting the module to the PC
[For T14, T16, TN18]
- Turn on the PC and connect the module to the PC in the following order: ① USB3 cable ② USB2 cable.
[For T18PE, T18, T68PE]
- Turn on the PC and connect the module to the PC with the included cable.
3.2. STEP 2. Installing the driver
- Insert the included CD-ROM.
- Right-click the PC's start button and start Device Manager.
[For T14, T16, TN18, T18PE, T68PE]
T14, T16, TN18 T18PE, T68PE T18
Radar module main unit ○ - ○
Radar module set (main unit, connection cable, USB-serial conversion module)
- ○ -
USB cable
USB2 (A-microB)
USB3 (A-microB)
USB2 (A-C) USB3 (A-C)
Start guide (this manual) ○ ○ ○
CD-ROM (software, USB driver, manual)
○ ○ ○
No.ST219-0007-Q01(Rev1.6)
3/11
・Right-click "Quad RS232-HS" and select "Update driver".
・Select "Browse my computer for driver".
・Click the "Browse" button and select the TitanDemoKitApp\Software\Driver folder on the CD-ROM,
and click the "Next" button.
No.ST219-0007-Q01(Rev1.6)
4/11
・Click the "Close" button.
・Repeat the same procedure for the remaining three "Quad RS232-HS".
・Right-click "USB Serial Port" and select "Update Driver".
No.ST219-0007-Q01(Rev1.6)
5/11
・Select "Browse my computer for drivers".
・Click the "Browse" button to select the TitanDemoKitApp\Software\Driver folder on the CD-ROM,
and click the "Next" button.
・Click the "Close" button.
・Repeat the same procedure for the remaining three "USB Serial Port".
No.ST219-0007-Q01(Rev1.6)
6/11
[For T18]
・Right-click "FTDI SuperSpeed-FOFO Bridge" and select "Update Driver".
・Select "Browse my computer for drivers".
No.ST219-0007-Q01(Rev1.6)
7/11
・Click the "Browse" button and select the TitanDemoKitApp\Software\Driver folder on the CD-ROM,
and then click the "Next" button.
・Click the "Close" button.
No.ST219-0007-Q01(Rev1.6)
8/11
[If Microsoft Visual C++ 2015 Redistributable(x86) is not installed on the PC]
・Open vc_redist.x86.exe in the TitanDemoKitApp\Software\Driver folder on the CD-ROM.
・Check "I accept the license terms and conditions" and click the "Install" button.
・Click the "Close" button.
3.3. STEP 3. Installing the software

- Select the CD-ROM in Explorer and copy the six files (Camera.dll,
FTD2XX_NET.dll, FTD3XX.dll, FTD3XX_NET.dll, MathNet.Numerics.dll, TitanDemoKitApp.exe) in the TitanDemoKitApp\Software folder and the CFG file in the folder with the same name as the frequency band of the evaluation module to be used in the Config folder to any folder.

The CFG file is used in STEP 6. Loading the CFG file.

3.4. STEP 4. Starting the software

- Open the TitanDemoKitApp.exe copied in STEP 3.

- The software will start.

No.ST219-0007-Q01(Rev1.6)
9/11
3.5. STEP 5. Connecting to the module

- Click Select port in the software.
・For modules other than T18, select the smallest of the four consecutive COM numbers of the connected module.
*To identify the target module, temporarily unplug the USB cable from the PC and click Select Port.
The module you are targeting will be the one that is not displayed in the list at this time.
For T18, select the TTN number.
・Click the Connect button.
・Once communication with the module is established, the Connect button will change to a Disconnect button.
The module's platform name and
フィードバックを送信
文字数制限は 5,000 文字です。さらに翻訳するには、矢印を使用してください。

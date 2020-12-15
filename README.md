# WinUI3Preview3_Problems_GridSplitter

This repository contains two solutions with sample code demonstrating the difference between the GridSplitter in UWP and WinUI3 Preview 3 Desktop.

The UWP sample code works as expected - as the user hovers over the GridSplitter the cursor changes to the Resize symbol. However, the in the WinUI3 Desktop sample code, the cursor does not change to the Resize cursor icon on the hover over or while adjusting the GridSplitter.

----

**Describe the bug**

In WinUI3 Preview3, the cursor does not change to the Resize cursor icon while adjusting the GridSplitter as it does in UWP.

**Steps to reproduce the bug**
1. Clone the repository.
2. Go to the GridSplitterWinUIPreview3 folder.
3. Open the GridSplitterWinUIPreview3 solution in Visual Studio 2019 Preview.
4. Build and run with Debug x64.
5. Hover over one of the two GridSplitters (Horizontal or Vertical). You should see the cursor icon does not change to the Resize icon.

**Expected behavior**

We expect the cursor icon to change to the Resize icon when hovering over the GridSplitter.

**Screenshots**

![GridSplitterExpectedBehavior](https://github.com/eleanorleffler/WinUI3Preview3_Problems_GridSplitter/blob/main/Screenshots/ExpectedBehavior.png)

Screenshot#1 - Expected Behavior

![GridSplitterCurrentBehavior](https://github.com/eleanorleffler/WinUI3Preview3_Problems_GridSplitter/blob/main/Screenshots/CurrentBehavior.PNG)

Screenshot#2 - Current Behavior

**Version Info**

NuGet package version: 

[Microsoft.VCRTForwarders.140 1.0.6]
[Microsoft.WinUI 3.0.0-preview3.201113.0]

Targeting:
Target: Universal Windows
Target version: Windows 10, version 1809 (10.0; Build 17763)
Min version: Windows 10, version 1803 (10.0; Build 17134)

Windows app type:
| UWP              | Win32            |
| :--------------- | :--------------- |
| 		Yes 	   |  				  |

| Windows 10 version                  | Saw the problem? |
| :--------------------------------- | :-------------------- |
| Insider Build (xxxxx)              | 						 |
| May 2020 Update (19041)            | 						 |
| November 2019 Update (18363)       | 						 |
| May 2019 Update (18362)            | 						 |
| October 2018 Update (17763)        | 			Yes			 |
| April 2018 Update (17134)          | 						 |
| Fall Creators Update (16299)       | 						 |
| Creators Update (15063)            | 						 |

| Device form factor | Saw the problem? |
| :----------------- | :--------------- |
| Desktop            | 		Yes			|
| Xbox               | 					|
| Surface Hub        | 					|
| IoT                | 					|

**Additional context**

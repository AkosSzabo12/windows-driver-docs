---
title: CCD APIs
description: Connecting and Configuring Display (CCD) APIs
ms.assetid: b71c1582-a91c-49d8-a3a3-d20f7746c354
keywords:
- connecting displays WDK Windows 7 display , CCD APIs
- connecting displays WDK Windows Server 2008 R2 display , CCD APIs
- configuring displays WDK Windows 7 display , CCD APIs
- configuring displays WDK Windows Server 2008 R2 display , CCD APIs
- CCD APIs WDK Windows 7 display
- CCD APIs WDK Windows Server 2008 R2 display
ms.date: 10/11/2018
ms.localizationpriority: medium
---

# CCD APIs


The connecting and configuring display (CCD) APIs in this section applies only to Windows 7 and later, and Windows Server 2008 R2 and later versions of Windows operating system.

## CCD Reference for User Mode Display Drivers

This section contains reference pages that provide support for connecting and configuring user mode displays. The functions are called by user mode display drivers.


**CCD Functions**

**[DisplayConfigGetDeviceInfo](/windows/desktop/api/winuser/nf-winuser-displayconfiggetdeviceinfo)**: [DisplayConfigSetDeviceInfo](/windows/desktop/api/winuser/nf-winuser-displayconfigsetdeviceinfo)

**[GetDisplayConfigBufferSizes](/windows/desktop/api/winuser/nf-winuser-getdisplayconfigbuffersizes)**: [QueryDisplayConfig](/windows/desktop/api/winuser/nf-winuser-querydisplayconfig)

**[SetDisplayConfig](/windows/desktop/api/winuser/nf-winuser-setdisplayconfig)**: 


 
**CCD Structures**

**[DISPLAYCONFIG_2DREGION](/windows/desktop/api/wingdi/ns-wingdi-displayconfig_2dregion)**: [DISPLAYCONFIG_ADAPTER_NAME](/windows/desktop/api/wingdi/ns-wingdi-displayconfig_adapter_name)

**[DISPLAYCONFIG_DEVICE_INFO_HEADER](/windows/desktop/api/wingdi/ns-wingdi-displayconfig_device_info_header)**: [DISPLAYCONFIG_MODE_INFO](/windows/desktop/api/wingdi/ns-wingdi-displayconfig_mode_info)

**[DISPLAYCONFIG_PATH_INFO](/windows/desktop/api/wingdi/ns-wingdi-displayconfig_path_info)**: [DISPLAYCONFIG_PATH_SOURCE_INFO](/windows/desktop/api/wingdi/ns-wingdi-displayconfig_path_source_info)

**[DISPLAYCONFIG_PATH_TARGET_INFO](/windows/desktop/api/wingdi/ns-wingdi-displayconfig_path_target_info)**: [DISPLAYCONFIG_RATIONAL](/windows/desktop/api/wingdi/ns-wingdi-displayconfig_rational)

**[DISPLAYCONFIG_SET_TARGET_PERSISTENCE](/windows/desktop/api/wingdi/ns-wingdi-displayconfig_set_target_persistence)**: [DISPLAYCONFIG_SOURCE_DEVICE_NAME](/windows/desktop/api/wingdi/ns-wingdi-displayconfig_source_device_name)

**[DISPLAYCONFIG_SOURCE_MODE](/windows/desktop/api/wingdi/ns-wingdi-displayconfig_source_mode)**: [DISPLAYCONFIG_TARGET_DEVICE_NAME](/windows/desktop/api/wingdi/ns-wingdi-displayconfig_target_device_name)

**[DISPLAYCONFIG_TARGET_DEVICE_NAME_FLAGS](/windows/desktop/api/wingdi/ns-wingdi-displayconfig_target_device_name_flags)**: [DISPLAYCONFIG_TARGET_MODE](/windows/desktop/api/wingdi/ns-wingdi-displayconfig_target_mode)

**[DISPLAYCONFIG_TARGET_PREFERRED_MODE](/windows/desktop/api/wingdi/ns-wingdi-displayconfig_target_preferred_mode)**: [DISPLAYCONFIG_VIDEO_SIGNAL_INFO](/windows/desktop/api/wingdi/ns-wingdi-displayconfig_video_signal_info)


 
**CCD Enumerations**

**[DISPLAYCONFIG_DEVICE_INFO_TYPE](/windows/desktop/api/wingdi/ne-wingdi-displayconfig_device_info_type)**: [DISPLAYCONFIG_MODE_INFO_TYPE](/windows/desktop/api/wingdi/ne-wingdi-displayconfig_mode_info_type)

**[DISPLAYCONFIG_PIXELFORMAT](/windows/desktop/api/wingdi/ne-wingdi-displayconfig_pixelformat)**: [DISPLAYCONFIG_ROTATION](/windows/desktop/api/wingdi/ne-wingdi-displayconfig_rotation)

**[DISPLAYCONFIG_SCALING](/windows/desktop/api/wingdi/ne-wingdi-displayconfig_scaling)**: [DISPLAYCONFIG_SCANLINE_ORDERING](/windows/desktop/api/wingdi/ne-wingdi-displayconfig_scanline_ordering)

**[DISPLAYCONFIG_TOPOLOGY_ID](/windows/desktop/api/wingdi/ne-wingdi-displayconfig_topology_id)**: [DISPLAYCONFIG_VIDEO_OUTPUT_TECHNOLOGY](/windows/desktop/api/wingdi/ne-wingdi-displayconfig_video_output_technology)



The following sections describe the CCD APIs and show how to use them in some example code:

[CCD Summaries and Scenarios](ccd-summaries-and-scenarios.md)

[CCD Example Code](ccd-example-code.md)

 


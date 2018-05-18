---
Description: 'Lists sources of WMI examples, code samples, books, TechNet ScriptCenter, and other websites. Download sources for CIM Studio, WMI Tools, WMI Event Viewer, WMI Event Registration, Object Browser, WMI SDK.'
audience: developer
author: 'REDMOND\\markl'
manager: 'REDMOND\\markl'
ms.assetid: '40216c7d-e359-4102-b990-334ba355ca77'
ms.prod: 'windows-server-dev'
ms.technology: 'windows-management-instrumentation'
ms.tgt_platform: multiple
title: Further Information
---

# Further Information

You can find resources and examples for using WMI in the following print and online sources:

-   [Print](#print)
-   [Online Documentation and Examples](#online-documentation-and-examples)
-   [MSDN Scripting](#msdn-scripting)
-   [Downloads](#downloads)
-   [Related topics](#related-topics)

## Print

The following printed material is available to help you learn more about WMI:

-   Lavy, Matthew and Megitt, Ashley *Windows Management Instrumentation (WMI).*

    New Riders Publishing; ISBN: 1578702607; 1st edition (October 15, 2001).

-   Lissoir, Alain *Understanding Windows Management Instrumentation (WMI) Scripting.*

    Digital Press; ISBN: 1555582664 (March 2003).

-   Lissoir, Alain *Leveraging Windows Management Instrumentation (WMI) Scripting.*

    Digital Press; ISBN: 1555582990 (March 2003).

    Includes a section on secure scripting and the use of security descriptors.

-   Golomshtok, Alexander *.NET System Management Services.*

    Apress; ISBN 1-59059-058-9 (April 8, 2003).

-   The Microsoft Windows Resource Kit Scripting Team *Microsoft Windows 2000 Scripting Guide.*

    Microsoft Press; ISBN: 0735618674; 1st edition (December 16, 2002).

-   Tunstall, Carig and Cole, Gwyn *Developing WMI Solutions: A Guide to Windows Management Instrumentation.*

    Addison Wesley Professional; ISBN: 0201616130; 1st edition (November 12, 2002).

    Includes information for writing WMI providers.

-   Policht, Marcin *WMI Essentials for Automating Windows Management.*

    Sams; ISBN: 0672321440; 1st edition (July 23, 2001).

-   Martinsson, Tobias

    *Scripting XML and WMI for Professional Developer's Guide.*

    John Wiley & Sons; ISBN: 0471399515; Book & CD edition (January 12, 2001).

-   Wilson, Ed *Microsoft Windows Scripting with WMI: Self-Paced Learning Guide.*

    Microsoft Press; ISBN: 0735622310 (November 2005).

    Tutorial format for beginning scripters that includes WMI scripts for more than 100 WMI classes.

## Online Documentation and Examples

The following online documentation and examples are available to help you learn to use WMI:

-   The most up-to-date version of WMI SDK documentation is on the MSDN Library. This documentation is located under Win32 and COM Development \| Administration and Management \| Windows Management Instrumentation.
-   [TechNet ScriptCenter](Http://go.microsoft.com/fwlink/p/?linkid=46710)

    Search by category and task to find short administrative scripts. For example, in the Monitoring category, you can find a script titled "Monitor Available Disk Space".

-   [TechNet scripting articles: Tales from the Script](Http://go.microsoft.com/fwlink/p/?linkid=84424)

    Articles about topics such as how to run WMI scripts on remote computers or use WMI events. Each article provides examples.

-   Microsoft Developer Network (MSDN) articles

    Articles about the basics of WMI administrator scripting. Each article provides examples.

    [WMI Scripting Primer: Part 1](Http://go.microsoft.com/fwlink/p/?linkid=84314)

    [WMI Scripting Primer: Part 2](Http://go.microsoft.com/fwlink/p/?linkid=84315)

    [WMI Scripting Primer: Part 3](Http://go.microsoft.com/fwlink/p/?linkid=84312)

-   WMI Blog

    You can search for posts on WMI at [http://blogs.msdn.com/wmi/default.aspx](Http://go.microsoft.com/fwlink/p/?linkid=84294).

-   [Scripting Guide](Http://go.microsoft.com/fwlink/p/?linkid=84421)

    A comprehensive overview of the scripting technologies available in the Windows operating systems, including WMI. This Microsoft TechNet website offers hundreds of administrator scripting examples and information about how to modify them for the needs of your system.

## MSDN Scripting

The Scripting Clinic under [Columns](Http://go.microsoft.com/fwlink/p/?linkid=84304) includes advanced scripting topics besides the WMI Scripting Primers, such as [Creating user accounts](Http://go.microsoft.com/fwlink/p/?linkid=84313) from Excel data.

## Downloads



| SDK name                                                                              | Windows Server version | URL (download link)                                               | Location                                               |
|---------------------------------------------------------------------------------------|------------------------|-------------------------------------------------------------------|--------------------------------------------------------|
| Microsoft Windows Software Development Kit (SDK) for Windows 7 and .NET Framework 4.0 | Windows Server 2008 R2 | <http://www.microsoft.com/download/en/confirmation.aspx?id=8279>  | %Install Path%\\Microsoft SDKs\\Windows\\v7.1\\Samples |
| Microsoft Windows Software Development Kit (SDK)                                      | Windows Server 2008    | <http://www.microsoft.com/download/en/confirmation.aspx?id=11310> | %Install Path%\\Microsoft SDKs\\Windows\\v6.1          |



 

CIM\_Studio and other WMI Administrative Tools can be downloaded from [WMI Administrative Tools](Http://go.microsoft.com/fwlink/p/?linkid=84420).

The WMI tools include:

-   WMI CIM Studio

    The CIM Studio tool allows you to work with WMI classes and namespaces in the CIM repository. It is also an important tool for WMI provider development because it helps in the initial WMI class creation in the CIM repository.

    WMI CIM Studio provides the ability to:

    -   Connect to a chosen system and browse the CIM repository in any namespace available.
    -   Search for classes by their name, descriptions, or property names.
    -   Review the properties, methods, and associations related to a given class.
    -   See the instances available for a given class.
    -   Perform queries in the WQL language.
    -   Generate a MOF file based on selected classes.
    -   Compile a MOF file you want to load in the CIM repository.

-   WMI Object Browser

    The Object Browser allows you to view the WMI objects present on your computer. The root of the hierarchy is the instance of [**Win32\_ComputerSystem**](https://msdn.microsoft.com/library/aa394102) that represents your computer system. Using the Object Browser, you can edit property values and qualifiers and run methods.

-   WMI Event Registration

    The Event Registration tool allows you to create, display, and modify event consumers, filters, and timers for a specified namespace. It is a tool for both developers and system administrators.

-   WMI Event Viewer

    You can use the Event Viewer to display the occurrence of WMI events you have configured in the WMI Event Registration.

You can download PowerShell RC1 and documentation at [http://www.microsoft.com/technet/scriptcenter/topics/msh/download.mspx](Http://go.microsoft.com/fwlink/p/?linkid=84436).

> [!Note]  
> These books and resources may not be available in some languages and countries or regions.

 

## Related topics

<dl> <dt>

[About WMI](about-wmi.md)
</dt> </dl>

 

 



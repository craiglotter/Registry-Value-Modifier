# Registry Value Modifier

Registry Value Modifier is a simple console application that sets the string data value of the specified registry key.

Usage:
   ApplicationName [RegistryRoot] [RegistryKey] [ValueName] [Data]
   where
     [RegistryRoot] is the registry root key, e.g. HKEY_LOCAL_MACHINE
     [RegistryKey] is the actual fully qualified key minus the root key, e.g. SOFTWARE\Microsoft
     [ValueName] is the name of the Value for which the data is to be set
     [Data] is the actual string value to be used in modifying the registry value
Example:
  "Registry Value Retriever.exe" "HKEY_LOCAL_MACHINE" "SOFTWARE\Microsoft\.NETFramework" "InstallRoot" "C:\wwwroot"
Output:
  Success.

Created by Craig Lotter, January 2006

*********************************

Project Details:

Coded in Visual Basic .NET using Visual Studio .NET 2003
Implements concepts such as Registry Programming.
Level of Complexity: simple

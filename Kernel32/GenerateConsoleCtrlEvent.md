## GenerateConsoleCtrlEvent

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GenerateConsoleCtrlEvent(
   uint dwCtrlEvent,
   uint dwProcessGroupId
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/console/generateconsolectrlevent)

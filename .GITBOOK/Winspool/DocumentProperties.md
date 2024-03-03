## DocumentProperties

```csharp
[DllImport("winspool.drv", SetLastError = true)]
public static extern int DocumentProperties(
   IntPtr hwnd,
   IntPtr hPrinter,
   string pDeviceName,
   IntPtr pDevModeOutput,
   IntPtr pDevModeInput,
   int fMode
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/printdocs/documentproperties)

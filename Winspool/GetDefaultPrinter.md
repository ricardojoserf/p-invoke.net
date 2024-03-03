## GetDefaultPrinter

```csharp
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool GetDefaultPrinter(
   StringBuilder pszBuffer,
   ref uint pcchBuffer
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/printdocs/getdefaultprinter)

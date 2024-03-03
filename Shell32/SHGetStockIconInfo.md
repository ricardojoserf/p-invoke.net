## SHGetStockIconInfo

```csharp
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHGetStockIconInfo(
   SHSTOCKICONID siid,
   SHGSI uFlags,
   ref SHSTOCKICONINFO psii
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-shgetstockiconinfo)

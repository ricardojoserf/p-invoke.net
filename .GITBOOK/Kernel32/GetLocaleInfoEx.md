## GetLocaleInfoEx

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern int GetLocaleInfoEx(
   string lpLocaleName,
   uint LCType,
   StringBuilder lpLCData,
   uint cchData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getlocaleinfoex)

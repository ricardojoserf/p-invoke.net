## GetLocaleInfo

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetLocaleInfo(
   uint Locale,
   uint LCType,
   StringBuilder lpLCData,
   uint cchData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getlocaleinfow)

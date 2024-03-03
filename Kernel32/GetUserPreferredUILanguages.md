## GetUserPreferredUILanguages

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetUserPreferredUILanguages(
   uint dwFlags,
   ref uint pulNumLanguages,
   StringBuilder pwszLanguagesBuffer,
   ref uint pcchLanguagesBuffer
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getuserpreferreduilanguages)

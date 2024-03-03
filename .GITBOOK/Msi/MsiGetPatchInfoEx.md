## MsiGetPatchInfoEx

```csharp
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiGetPatchInfoEx(
   [MarshalAs(UnmanagedType.LPTStr)] string szPatchCode,
   [MarshalAs(UnmanagedType.LPTStr)] string szProductCode,
   [MarshalAs(UnmanagedType.LPTStr)] string szUserSid,
   uint dwContext,
   [MarshalAs(UnmanagedType.LPTStr)] string szProperty,
   [MarshalAs(UnmanagedType.LPTStr)] StringBuilder lpValue,
   ref int pcchValue
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msigetpatchinfoexw)

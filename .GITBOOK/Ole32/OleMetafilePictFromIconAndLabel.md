## OleMetafilePictFromIconAndLabel

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleMetafilePictFromIconAndLabel(
   IntPtr hIcon,
   [MarshalAs(UnmanagedType.LPWStr)] string lpszLabel,
   [MarshalAs(UnmanagedType.LPWStr)] string lpszSourceFile,
   uint iIconIndex,
   out IMetafilePict ppole,
   [MarshalAs(UnmanagedType.Bool)] bool fIcon,
   [MarshalAs(UnmanagedType.Bool)] bool fOwn
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olemetafilepictfromiconandlabel)

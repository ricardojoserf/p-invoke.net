## URLDownloadToFile

```csharp
[DllImport("urlmon.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern int URLDownloadToFile(
   IntPtr pCaller,
   [MarshalAs(UnmanagedType.LPWStr)] string szURL,
   [MarshalAs(UnmanagedType.LPWStr)] string szFileName,
   int dwReserved,
   IntPtr lpfnCB
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/platform-apis/ms775123(v=vs.85))

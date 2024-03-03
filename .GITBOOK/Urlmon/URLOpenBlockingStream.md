## URLOpenBlockingStream

```csharp
[DllImport("urlmon.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern int URLOpenBlockingStream(
   IntPtr pCaller,
   [MarshalAs(UnmanagedType.LPWStr)] string szURL,
   out IntPtr ppStream,
   int dwReserved,
   IntPtr lpfnCB
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/platform-apis/ms775127(v=vs.85))

## FindMimeFromData

```csharp
[DllImport("urlmon.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern int FindMimeFromData(
   IntPtr pBC,
   [MarshalAs(UnmanagedType.LPWStr)] string pwzUrl,
   [MarshalAs(UnmanagedType.LPArray,
   ArraySubType = UnmanagedType.U1,
   SizeParamIndex = 3)] byte[] pBuffer,
   int cbSize,
   [MarshalAs(UnmanagedType.LPWStr)] string pwzMimeProposed,
   int dwMimeFlags,
   out IntPtr ppwzMimeOut,
   int dwReserved
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/platform-apis/ms775107(v=vs.85))

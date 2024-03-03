## NetShareAdd

```csharp
[DllImport("Comdlg32.dll", SetLastError = true)]
public static extern NET_API_STATUS NetShareAdd(
   [MarshalAs(UnmanagedType.LPWStr)] string servername,
   int level,
   ref SHARE_INFO_2 buf,
   out uint parm_err
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/lmshare/nf-lmshare-netshareadd)

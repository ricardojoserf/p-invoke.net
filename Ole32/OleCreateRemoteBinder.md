## OleCreateRemoteBinder

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleCreateRemoteBinder(
   [MarshalAs(UnmanagedType.LPWStr)] string lpszMachineName,
   IntPtr pAuthInfo,
   uint reserved1,
   [MarshalAs(UnmanagedType.LPWStr)] string lpszObjectName,
   out IBindCtx ppBindCtx
);
```

Microsoft documentation: (TODO)

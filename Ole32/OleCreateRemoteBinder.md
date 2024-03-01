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

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olecreateremotebinder)

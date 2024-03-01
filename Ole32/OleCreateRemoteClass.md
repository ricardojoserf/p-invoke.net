## OleCreateRemoteClass

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleCreateRemoteClass(
   [MarshalAs(UnmanagedType.LPWStr)] string lpszMachineName,
   ref Guid rclsid,
   ref Guid riid,
   out object ppv
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olecreateremoteclass)

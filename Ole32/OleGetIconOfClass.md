## OleGetIconOfClass

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleGetIconOfClass(
   ref Guid rclsid,
   [MarshalAs(
   UnmanagedType.LPWStr)] string lpszLabel,
   [MarshalAs(
   UnmanagedType.Bool)] bool fUseTypeAsLabel,
   out IntPtr phicon
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olegeticonofclass)

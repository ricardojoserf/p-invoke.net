## SHMessageBoxCheck

```
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern uint SHMessageBoxCheck(
   IntPtr hwnd,
   [MarshalAs(
   UnmanagedType.LPWStr)] string pszText,
   [MarshalAs(
   UnmanagedType.LPWStr)] string pszCaption,
   uint uType,
   int iDefault,
   [MarshalAs(
   UnmanagedType.LPWStr)] string pszRegVal
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-shmessageboxcheckw)

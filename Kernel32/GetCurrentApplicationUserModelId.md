## GetCurrentApplicationUserModelId

```
[DllImport("Shell32.dll", SetLastError = true, CharSet = CharSet.Unicode)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetCurrentApplicationUserModelId(
   ref uint AppModelIDLength,
   StringBuilder AppModelID
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-getcurrentapplicationusermodelid)

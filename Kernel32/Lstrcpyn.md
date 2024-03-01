## Lstrcpyn

```
[DllImport("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr lstrcpyn(
   StringBuilder lpString1,
   string lpString2,
   int iMaxLength
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-lstrcpynw)

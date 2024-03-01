## Lstrcat

```
[DllImport("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr lstrcat(StringBuilder lpString1,
   string lpString2
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-lstrcatw)

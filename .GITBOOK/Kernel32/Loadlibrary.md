## Loadlibrary

```
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr LoadLibrary(string lpLibFileName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-loadlibraryw)

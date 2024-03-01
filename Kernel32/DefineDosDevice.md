## DefineDosDevice

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DefineDosDevice(
   uint dwFlags,
   string lpDeviceName,
   string lpTargetPath
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-definedosdevicew)

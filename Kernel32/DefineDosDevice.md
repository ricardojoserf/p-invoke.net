## DefineDosDevice

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DefineDosDevice(
   uint dwFlags,
   string lpDeviceName,
   string lpTargetPath
);
```

Microsoft documentation: (TODO)

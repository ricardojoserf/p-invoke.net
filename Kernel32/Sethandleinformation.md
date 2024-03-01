## Sethandleinformation

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetHandleInformation(IntPtr hObject,
   uint dwMask,
   uint dwFlags
);
```

Microsoft documentation: (TODO)

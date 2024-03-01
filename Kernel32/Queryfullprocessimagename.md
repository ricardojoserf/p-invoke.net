## Queryfullprocessimagename

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool QueryFullProcessImageName(IntPtr hProcess,
   uint dwFlags,
   StringBuilder lpExeName,
   ref uint lpdwSize
);
```

Microsoft documentation: (TODO)

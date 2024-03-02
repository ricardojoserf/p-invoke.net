## Replacefile

```
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ReplaceFile(string lpReplacedFileName,
   string lpReplacementFileName,
   string lpBackupFileName,
   uint dwReplaceFlags,
   IntPtr lpExclude,
   IntPtr lpReserved
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/fileio/moving-and-replacing-files#:~:text=The%20ReplaceFile%20function%20replaces%20one,an%20application%20can%20move%20it.)

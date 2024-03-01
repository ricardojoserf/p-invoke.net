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

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-replacefile)

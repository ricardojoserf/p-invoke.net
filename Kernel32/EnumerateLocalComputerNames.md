## EnumerateLocalComputerNames

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumerateLocalComputerNames(
   COMPUTER_NAME_FORMAT NameType,
   uint dwFlags,
   ref uint nSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-enumeratelocalcomputernamesw)

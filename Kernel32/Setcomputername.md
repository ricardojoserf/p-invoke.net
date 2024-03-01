## Setcomputername

```
[DllImport("Kernel32.dll", CharSet = CharSet.Ansi, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetComputerName(
   string lpComputerName
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setcomputernamea)

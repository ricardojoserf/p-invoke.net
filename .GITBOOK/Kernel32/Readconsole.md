## Readconsole

```
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ReadConsole(IntPtr hConsoleInput,
   [Out] StringBuilder lpBuffer,
   uint nNumberOfCharsToRead,
   out uint lpNumberOfCharsRead,
   IntPtr lpReserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/readconsole)

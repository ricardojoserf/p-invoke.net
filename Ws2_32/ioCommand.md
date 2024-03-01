## ioCommand

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int ioCommand(
   IntPtr s,
   int cmd,
   ref uint argp
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/winsock/iocommand)

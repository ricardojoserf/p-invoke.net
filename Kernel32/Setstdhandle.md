## Setstdhandle

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetStdHandle(
   uint nStdHandle,
   IntPtr hHandle
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/setstdhandle)

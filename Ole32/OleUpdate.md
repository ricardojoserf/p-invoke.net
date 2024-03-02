## OleUpdate

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleUpdate(
   IAdviseSink pAdvSink,
   uint dwReserved
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/oleidl/ne-oleidl-oleupdate)

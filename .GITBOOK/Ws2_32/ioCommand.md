## ioCommand

```csharp
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int ioCommand(
   IntPtr s,
   int cmd,
   ref uint argp
);
```


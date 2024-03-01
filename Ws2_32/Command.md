## Command

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int Command(
   IntPtr s,
   int cmd,
   ref ulong argp,
   ref uint arg
);
```

[Microsoft documentation](TODO)

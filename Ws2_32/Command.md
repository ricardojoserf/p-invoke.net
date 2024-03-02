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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/windows-commands)

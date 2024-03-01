## NetRemoteTOD

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetRemoteTOD(
   string UncServerName,
   out IntPtr Buffer
);
```

Microsoft documentation: (TODO)

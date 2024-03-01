## SetThreadToken

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetThreadToken(
   IntPtr Thread,
   IntPtr Token
);
```

[Microsoft documentation](TODO)

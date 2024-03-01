## Setenvironmentvariable

```
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetEnvironmentVariable(string lpName,
   string lpValue
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processenv/nf-processenv-setenvironmentvariablew)

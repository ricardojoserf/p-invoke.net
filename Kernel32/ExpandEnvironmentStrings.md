## ExpandEnvironmentStrings

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern uint ExpandEnvironmentStrings(
   string lpSrc,
   [Out] StringBuilder lpDst,
   uint nSize
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/processenv/nf-processenv-expandenvironmentstringsa)

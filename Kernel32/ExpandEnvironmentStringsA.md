## ExpandEnvironmentStringsA

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern uint ExpandEnvironmentStringsA(string lpSrc, [Out]
StringBuilder lpDst, uint nSize);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-expandenvironmentstringsa)

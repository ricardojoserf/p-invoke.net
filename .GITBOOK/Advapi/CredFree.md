## CredFree

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CredFree(
   IntPtr Buffer
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credfree)

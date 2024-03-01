## DdeInitialize

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr DdeInitializeA(ref uint pidInst,
   IntPtr pfncallback,
   uint afCmd,
   uint ulRes
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-ddeinitializea)

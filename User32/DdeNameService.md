## DdeNameService

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr DdeNameService(
   IntPtr idInst,
   IntPtr hsz1,
   IntPtr hsz2,
   uint afCmd
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-ddenameservice)

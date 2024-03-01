## GetUserName

```
[DllImport("Advapi32.dll", SetLastError = true)]
public static extern bool GetUserName(
   StringBuilder lpBuffer,
   ref uint nSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getusernamea)

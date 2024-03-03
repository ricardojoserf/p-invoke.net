## DdeSetUserHandle

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr DdeSetUserHandle(
   IntPtr idInst,
   uint wUser,
   IntPtr hUser
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ddeml/nf-ddeml-ddesetuserhandle)

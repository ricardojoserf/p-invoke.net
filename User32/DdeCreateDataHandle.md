## DdeCreateDataHandle

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr DdeCreateDataHandle(
   IntPtr idInst,
   byte[] pSrc,
   uint cb,
   uint cbOff,
   IntPtr hszItem,
   uint wFmt,
   uint afCmd
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-ddecreatedatahandle)

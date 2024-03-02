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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ddeml/nf-ddeml-ddecreatedatahandle)

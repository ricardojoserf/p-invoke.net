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

[Microsoft documentation](TODO)

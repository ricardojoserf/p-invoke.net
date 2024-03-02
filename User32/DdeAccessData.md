## DdeAccessData

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr DdeAccessData(
   IntPtr hData,
   out uint pcbDataSize
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ddeml/nf-ddeml-ddeaccessdata)

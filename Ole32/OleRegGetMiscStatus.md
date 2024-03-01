## OleRegGetMiscStatus

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleRegGetMiscStatus(
   ref Guid clsid,
   uint dwAspect,
   out uint pdwStatus
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olereggetmiscstatus)

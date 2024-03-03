## CoRegisterMessageFilter

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoRegisterMessageFilter(
   IMessageFilter lpcf,
   out IMessageFilter lppcf
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/objbase/nf-objbase-coregistermessagefilter)

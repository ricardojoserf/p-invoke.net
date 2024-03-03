## OleSetAutoConvert

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleSetAutoConvert(
   ref Guid clsidOld,
   ref Guid clsidNew
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olesetautoconvert)

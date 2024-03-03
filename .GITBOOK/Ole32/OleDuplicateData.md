## OleDuplicateData

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleDuplicateData(
   HANDLE hSrc,
   uint cfFormat,
   uint uiFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-oleduplicatedata)

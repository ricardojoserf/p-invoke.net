## OleRegEnumVerbs

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleRegEnumVerbs(
   ref Guid clsid,
   out IEnumOLEVERB ppenum
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-oleregenumverbs)

## OleSave

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleSave(
   IStorage pStg,
   IStream pStm,
   [MarshalAs(UnmanagedType.Bool)] bool fSameAsLoad
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olesave)

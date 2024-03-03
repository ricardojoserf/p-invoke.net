## StgOpenStorage

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StgOpenStorage(
   [MarshalAs(UnmanagedType.LPWStr)] string pwcsName,
   IStorage pstgPriority,
   uint grfMode,
   IntPtr snbExclude,
   uint reserved,
   out IStorage ppstgOpen
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/coml2api/nf-coml2api-stgopenstorage)

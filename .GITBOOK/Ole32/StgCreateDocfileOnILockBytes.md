## StgCreateDocfileOnILockBytes

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StgCreateDocfileOnILockBytes(
   ILockBytes plkbyt,
   uint grfMode,
   uint reserved,
   out IStorage ppstgOpen
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/coml2api/nf-coml2api-stgcreatedocfileonilockbytes)

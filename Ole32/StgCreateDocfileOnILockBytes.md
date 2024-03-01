## StgCreateDocfileOnILockBytes

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StgCreateDocfileOnILockBytes(
   ILockBytes plkbyt,
   uint grfMode,
   uint reserved,
   out IStorage ppstgOpen
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-stgcreatedocfileonilockbytes)

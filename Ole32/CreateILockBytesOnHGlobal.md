## CreateILockBytesOnHGlobal

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CreateILockBytesOnHGlobal(
   IntPtr hGlobal,
   bool fDeleteOnRelease,
   out ILockBytes ppLkbyt
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/objidl/nf-objidl-createilockbytesonhglobal)

## CreateILockBytesOnHGlobal

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CreateILockBytesOnHGlobal(
   IntPtr hGlobal,
   bool fDeleteOnRelease,
   out ILockBytes ppLkbyt
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/coml2api/nf-coml2api-createilockbytesonhglobal)

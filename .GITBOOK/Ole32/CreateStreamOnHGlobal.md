## CreateStreamOnHGlobal

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CreateStreamOnHGlobal(
   IntPtr hGlobal,
   bool fDeleteOnRelease,
   out IStream ppstm
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-createstreamonhglobal)

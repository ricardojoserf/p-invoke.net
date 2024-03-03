## EnumProcessModules

```
[DllImport("psapi.dll", SetLastError = true)]
public static extern bool EnumProcessModules(
   IntPtr hProcess,
   [MarshalAs(UnmanagedType.LPArray,
   ArraySubType = UnmanagedType.U4)] [In,
   Out] uint[] lphModule,
   uint cb,
   out uint lpcbNeeded
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/psapi/nf-psapi-enumprocessmodules)

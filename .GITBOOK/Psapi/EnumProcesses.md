## EnumProcesses

```csharp
[DllImport("psapi.dll", SetLastError = true)]
public static extern bool EnumProcesses(
   [MarshalAs(UnmanagedType.LPArray,
   ArraySubType = UnmanagedType.U4)] [In,
   Out] uint[] lpidProcess,
   uint cb,
   out uint lpcbNeeded
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/psapi/nf-psapi-enumprocesses)

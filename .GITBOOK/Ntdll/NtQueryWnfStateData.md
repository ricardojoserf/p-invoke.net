## NtQueryWnfStateData

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtQueryWnfStateData(
   ref long StateId,
   IntPtr ChangeStamp,
   IntPtr StateData,
   uint StateDataSize,
   out uint RetLength,
   bool Persist
);
```


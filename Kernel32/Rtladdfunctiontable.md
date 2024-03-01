## Rtladdfunctiontable

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool RtlAddFunctionTable(
   ref RUNTIME_FUNCTION FunctionTable,
   uint EntryCount,
   uint64 BaseAddress
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/rtlapi/nf-rtlapi-rtladdfunctiontable)

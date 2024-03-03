## Rtladdfunctiontable

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool RtlAddFunctionTable(ref RUNTIME_FUNCTION FunctionTable,
   uint EntryCount,
   uint64 BaseAddress
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winnt/nf-winnt-rtladdfunctiontable)

## CoInitializeEx

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoInitializeEx(
   IntPtr pvReserved,
   uint dwCoInit
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-coinitializeex)

## CLSIDFromProgID

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CLSIDFromProgID(
   [MarshalAs(UnmanagedType.LPWStr)] string lpszProgID,
   out Guid pclsid
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-clsidfromprogid)

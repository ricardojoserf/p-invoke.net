## CoRegisterSurrogate

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoRegisterSurrogate(
   IAdviseSink pSurrogate,
   out IntPtr ppErrorObj
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-coregistersurrogate)

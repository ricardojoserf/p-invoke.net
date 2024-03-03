## CoGetStdMarshalEx

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoGetStdMarshalEx(
   IUnknown pUnkOuter,
   uint smexflags,
   out IntPtr ppMarshal
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cogetstdmarshalex)

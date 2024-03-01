## CoGetStdMarshalEx

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoGetStdMarshalEx(
   IUnknown pUnkOuter,
   uint smexflags,
   out IntPtr ppMarshal
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cogetstdmarshalex)

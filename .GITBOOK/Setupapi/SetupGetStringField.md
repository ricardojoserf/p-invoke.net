## SetupGetStringField

```
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetupGetStringField(
   IntPtr Context,
   uint FieldIndex,
   StringBuilder ReturnBuffer,
   uint ReturnBufferSize,
   out uint RequiredSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/setupapi/nf-setupapi-setupgetstringfieldw)

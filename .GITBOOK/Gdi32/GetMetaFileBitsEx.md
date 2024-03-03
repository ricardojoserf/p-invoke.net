## GetMetaFileBitsEx

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint GetMetaFileBitsEx(
   IntPtr hmf,
   uint cbBuffer,
   byte[] lpData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getmetafilebitsex)

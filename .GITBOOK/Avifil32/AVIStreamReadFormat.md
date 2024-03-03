## AVIStreamReadFormat

```csharp
[DllImport("Avifil32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint AVIStreamReadFormat(
   IntPtr pAVIStream,
   int lPos,
   IntPtr lpFormat,
   ref int lpcbFormat
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/vfw/nf-vfw-avistreamreadformat)

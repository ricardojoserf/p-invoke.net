## GetEnhMetaFileDescription

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint GetEnhMetaFileDescription(
   IntPtr hemf,
   uint cchBuffer,
   StringBuilder lpDescription
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getenhmetafiledescriptiona)

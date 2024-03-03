## CopyEnhMetaFile

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr CopyEnhMetaFile(
   IntPtr hemfSrc,
   string lpszFile
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-copyenhmetafilea)

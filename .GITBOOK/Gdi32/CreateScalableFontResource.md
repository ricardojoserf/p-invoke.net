## CreateScalableFontResource

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr CreateScalableFontResource(
   uint fdwHidden,
   string lpszFont,
   string lpszFile,
   string lpszPath
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-createscalablefontresourcea)

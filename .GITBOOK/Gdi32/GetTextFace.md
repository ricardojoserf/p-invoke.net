## GetTextFace

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int GetTextFace(
   IntPtr hdc,
   int nCount,
   StringBuilder lpFaceName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-gettextfacea)

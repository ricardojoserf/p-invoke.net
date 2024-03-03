## GetPath

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int GetPath(
   IntPtr hdc,
   [Out] POINT[] lpPoints,
   [Out] byte[] lpTypes,
   int nSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getpath)

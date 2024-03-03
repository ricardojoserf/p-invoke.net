## CoLoadLibrary

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoLoadLibrary(
   string lpszLibName,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/objbase/nf-objbase-coloadlibrary)

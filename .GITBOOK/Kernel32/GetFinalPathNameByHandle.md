## GetFinalPathNameByHandle

```csharp
[DllImport("kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint GetFinalPathNameByHandle(
   IntPtr hFile,
   StringBuilder lpszFilePath,
   uint cchFilePath,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getfinalpathnamebyhandlew)

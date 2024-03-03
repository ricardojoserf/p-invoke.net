## GetTempFileName

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetTempFileName(
   string lpPathName,
   string lpPrefixString,
   uint uUnique,
   StringBuilder lpTempFileName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-gettempfilenamew)

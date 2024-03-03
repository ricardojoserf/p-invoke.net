## FindNextFile

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool FindNextFile(
   SafeFindHandle hFindFile,
   out WIN32_FIND_DATA lpFindFileData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-findnextfilew)

## GetFileInformationByHandle

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetFileInformationByHandle(
   SafeFileHandle hFile,
   out BY_HANDLE_FILE_INFORMATION lpFileInformation
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getfileinformationbyhandle)

## Setfileinformationbyhandle

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetFileInformationByHandle(IntPtr hFile,
   uint FileInformationClass,
   IntPtr lpFileInformation,
   uint dwBufferSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-setfileinformationbyhandle)

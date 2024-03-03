## GetFileAttributesEx

```csharp
[DllImport("kernel32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool GetFileAttributesEx(
   string lpFileName,
   GET_FILEEX_INFO_LEVELS fInfoLevelId,
   out WIN32_FILE_ATTRIBUTE_DATA lpFileInformation
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getfileattributesexa)

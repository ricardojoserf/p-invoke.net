## GetFileType

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetFileType(
   IntPtr hFile
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getfiletype)

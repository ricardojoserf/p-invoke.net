## FindNextChangeNotification

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool FindNextChangeNotification(
   IntPtr hChangeHandle
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-findnextchangenotification)

## CreateDirectoryEx

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CreateDirectoryEx(
   string lpTemplateDirectory,
   string lpNewDirectory,
   IntPtr lpSecurityAttributes
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-createdirectoryexa)

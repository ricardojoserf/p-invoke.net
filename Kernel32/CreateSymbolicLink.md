## CreateSymbolicLink

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CreateSymbolicLink(
   string lpSymlinkFileName,
   string lpTargetFileName,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-createsymboliclinkw)

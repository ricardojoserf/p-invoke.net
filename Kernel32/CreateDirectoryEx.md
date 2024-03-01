## CreateDirectoryEx

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CreateDirectoryEx(
   string lpTemplateDirectory,
   string lpNewDirectory,
   IntPtr lpSecurityAttributes
);
```

Microsoft documentation: (TODO)

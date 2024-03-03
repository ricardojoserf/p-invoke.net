## CreateHardLink

```csharp
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CreateHardLink(
   string lpFileName,
   string lpExistingFileName,
   IntPtr lpSecurityAttributes
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-createhardlinka)

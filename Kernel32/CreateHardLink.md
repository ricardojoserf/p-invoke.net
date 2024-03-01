## CreateHardLink

```
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CreateHardLink(
   string lpFileName,
   string lpExistingFileName,
   IntPtr lpSecurityAttributes
);
```

Microsoft documentation: (TODO)

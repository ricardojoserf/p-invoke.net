## SHGetDiskFreeSpace

```csharp
[DllImport("kernel32.dll", CharSet = CharSet.Unicode)]
public static extern bool SHGetDiskFreeSpace(
   string pszVolume,
   out ulong pqwFreeCaller,
   out ulong pqwTotal,
   out ulong pqwFree
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-shgetdiskfreespaceexw)

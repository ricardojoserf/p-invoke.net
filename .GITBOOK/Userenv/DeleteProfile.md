## DeleteProfile

```
[DllImport("userenv.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern bool DeleteProfile(
   IntPtr lpSidString,
   IntPtr lpProfilePath,
   IntPtr lpComputerName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/userenv/nf-userenv-deleteprofilew)

## RegDeleteValue

```
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int RegDeleteValue(
   IntPtr hKey,
   string lpValueName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdeletevaluew)

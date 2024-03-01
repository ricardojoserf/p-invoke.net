## ExtractIcon

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern IntPtr ExtractIcon(
   IntPtr hInst,
   string lpszExeFileName,
   uint nIconIndex
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-extracticonw)

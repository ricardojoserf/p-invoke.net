## ExtractAssociatedIcon

```
[DllImport("shell32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern IntPtr ExtractAssociatedIconA(
   IntPtr hInst,
   StringBuilder lpIconPath,
   out ushort lpiIcon
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-extractassociatedicona)

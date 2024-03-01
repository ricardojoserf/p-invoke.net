## ExtractAssociatedIcon

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern IntPtr ExtractAssociatedIcon(
   IntPtr hInst,
   StringBuilder lpIconPath,
   out ushort lpiIcon
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-extractassociatediconw)

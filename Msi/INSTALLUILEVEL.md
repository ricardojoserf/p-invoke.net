## INSTALLUILEVEL

```
DllImport("msi.dll", CharSet = CharSet.Auto)
public static extern int MsiDoAction(
   IntPtr hInstall,
   [MarshalAs(
   UnmanagedType.LPTStr)] string szAction
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/msi/installuilevel)

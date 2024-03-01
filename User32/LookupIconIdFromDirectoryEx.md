## LookupIconIdFromDirectoryEx

```
[DllImport("user32.dll", SetLastError = true)]
public static extern int LookupIconIdFromDirectoryEx(
   IntPtr presbits,
   bool fIcon,
   int cxDesired,
   int cyDesired,
   uint Flags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-lookupiconidfromdirectoryex)

## EnumICMProfiles

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int EnumICMProfiles(
   IntPtr hdc,
   ICMEnumProc proc,
   IntPtr lParam
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-enumicmprofilesa)

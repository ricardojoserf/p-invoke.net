## EnumPropsEx

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern int EnumPropsExA(IntPtr hWnd,
   PropEnumProcEx lpEnumFunc,
   IntPtr lParam
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-enumpropsexa)

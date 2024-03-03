## CheckMenuRadioItem

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CheckMenuRadioItem(
   IntPtr hmenu,
   uint idFirst,
   uint idLast,
   uint idCheck,
   uint uFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-checkmenuradioitem)

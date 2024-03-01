## CopyRect

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CopyRect(
   [Out] out RECT lprcDst,
   [In] ref RECT lprcSrc
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-copyrect)

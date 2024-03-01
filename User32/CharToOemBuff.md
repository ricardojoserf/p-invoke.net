## CharToOemBuff

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CharToOemBuff(
   [In] string lpszSrc,
   [Out] StringBuilder lpszDst,
   uint cchDstLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-chartooembuffw)

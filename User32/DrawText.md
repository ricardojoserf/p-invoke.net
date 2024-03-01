## DrawText

```
[DllImport("user32.dll", SetLastError = true)]
public static extern int DrawTextA(IntPtr hdc,
   string lpchText,
   int cchText,
   ref RECT lprc,
   uint format
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-drawtexta)

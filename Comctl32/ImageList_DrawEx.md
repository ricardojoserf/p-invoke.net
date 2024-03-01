## ImageList_DrawEx

```
[DllImport("Comctl32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ImageList_DrawEx(
   IntPtr himl,
   int i,
   IntPtr hdcDst,
   int x,
   int y,
   int dx,
   int dy,
   uint rgbBk,
   uint rgbFg,
   uint fStyle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/commctrl/nf-commctrl-imagelist_drawex)

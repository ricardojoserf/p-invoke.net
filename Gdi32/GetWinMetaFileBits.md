## GetWinMetaFileBits

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern uint GetWinMetaFileBits(
   IntPtr hemf,
   uint cbData16,
   byte[] pData16,
   int iMapMode,
   IntPtr hdcRef
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getwinmetafilebits)

## StartDoc

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int StartDoc(
   IntPtr hdc,
   [In] ref DOCINFO lpdi
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-startdoca)

## GetCurrencyFormat

```
[DllImport("Kernel32.dll", SetLastError = true, CharSet = CharSet.Unicode)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetCurrencyFormat(
   string Locale,
   uint dwFlags,
   string lpValue,
   [In] ref CURRENCYFMT lpFormat,
   StringBuilder lpCurrencyStr,
   int cchCurrency
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-getcurrencyformatw)

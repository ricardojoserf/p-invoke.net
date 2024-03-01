## CryptStringToBinary

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptStringToBinary(
   string pszString,
   uint cchString,
   uint dwFlags,
   byte[] pbBinary,
   ref uint pcbBinary,
   ref uint pdwSkip,
   ref uint pdwFlags
);
```

Microsoft documentation: (TODO)

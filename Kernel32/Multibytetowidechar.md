## Multibytetowidechar

```
[DllImport("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern int MultiByteToWideChar(
   uint CodePage,
   uint dwFlags,
   string lpMultiByteStr,
   int cbMultiByte,
   [Out] StringBuilder lpWideCharStr,
   int cchWideChar
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/stringapiset/nf-stringapiset-multibytetowidechar)

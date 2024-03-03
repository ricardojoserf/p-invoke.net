## FormatMessageW

```
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int FormatMessageW(
   int dwFlags,
   IntPtr lpSource,
   uint dwMessageId,
   int dwLanguageId,
   StringBuilder lpBuffer,
   int nSize,
   IntPtr va_list_arguments
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-formatmessagew)

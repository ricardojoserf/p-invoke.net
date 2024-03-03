## InternetFindNextFile

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool InternetFindNextFile(
   IntPtr hFind,
   ref WIN32_FIND_DATA lpvFindFileData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-internetfindnextfilea)

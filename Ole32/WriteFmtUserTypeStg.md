## WriteFmtUserTypeStg

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int WriteFmtUserTypeStg(
   IStorage pstg,
   uint cf,
   [MarshalAs(
   UnmanagedType.LPWStr)] string lpszUserType
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-writefmtusertypestg)

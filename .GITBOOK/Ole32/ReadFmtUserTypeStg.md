## ReadFmtUserTypeStg

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int ReadFmtUserTypeStg(
   IStorage pstg,
   out uint cf,
   out IntPtr lplpszUserType
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-readfmtusertypestg)

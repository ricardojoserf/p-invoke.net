## FindFirstFileEx

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)]
public static extern SafeFindHandle FindFirstFileEx(
   string lpFileName,
   FINDEX_INFO_LEVELS fInfoLevelId,
   out WIN32_FIND_DATA lpFindFileData,
   FINDEX_SEARCH_OPS fSearchOp,
   IntPtr lpSearchFilter,
   uint dwAdditionalFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-findfirstfileexw)

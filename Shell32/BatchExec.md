## BatchExec

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int BatchExec(
   IntPtr hwndOwner,
   string lpszCmdline,
   int dwCmdexecopt,
   ref string lpszOut,
   int lpszOutSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-batchexec)

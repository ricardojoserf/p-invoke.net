## InterlockedIncrement

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.I4)]
public static extern int InterlockedIncrement(
   ref int lpAddend
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnt/nf-winnt-interlockedincrement)

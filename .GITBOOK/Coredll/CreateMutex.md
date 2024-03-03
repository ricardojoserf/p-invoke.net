## CreateMutex

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern IntPtr CreateMutex(
   IntPtr lpMutexAttributes,
   bool bInitialOwner,
   string lpName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-createmutexa)

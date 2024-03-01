## WaitForMultipleObjects

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern uint WaitForMultipleObjects(
   uint nCount,
   IntPtr[] lpHandles,
   int fWaitAll,
   uint dwMilliseconds
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-waitformultipleobjects)

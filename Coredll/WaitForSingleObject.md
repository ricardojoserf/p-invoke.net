## WaitForSingleObject

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern uint WaitForSingleObject(
   IntPtr hHandle,
   uint dwMilliseconds
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-waitforsingleobject)

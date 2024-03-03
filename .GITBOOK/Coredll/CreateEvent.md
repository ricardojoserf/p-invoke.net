## CreateEvent

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern IntPtr CreateEvent(
   IntPtr lpEventAttributes,
   bool bManualReset,
   bool bInitialState,
   string lpName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-createeventa)

## MQSetQueueSecurity

```
[DllImport("Mqrt.dll", CharSet = CharSet.Unicode)]
public static extern uint MQSetQueueSecurity(
   string formatName,
   int SecurityInformation,
   IntPtr SecurityDescriptor
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/mq/nc-mq-pfncsetsecuritydescriptor)

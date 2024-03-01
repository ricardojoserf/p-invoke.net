## MQGetQueueSecurity

```
[DllImport("Mqrt.dll", CharSet = CharSet.Unicode)]
public static extern uint MQGetQueueSecurity(
   string formatName,
   int SecurityInformation,
   IntPtr SecurityDescriptor,
   int Length,
   out int LengthNeeded
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/mq/nc-mq-pfncgetsecuritydescriptor)

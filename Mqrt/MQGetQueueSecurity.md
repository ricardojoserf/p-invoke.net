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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/windows/desktop/msmq/ms703223(v=vs.85))

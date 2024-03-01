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

[Microsoft documentation](TODO)

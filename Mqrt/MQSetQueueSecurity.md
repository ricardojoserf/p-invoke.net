## MQSetQueueSecurity

```csharp
[DllImport("Mqrt.dll", CharSet = CharSet.Unicode)]
public static extern uint MQSetQueueSecurity(
   string formatName,
   int SecurityInformation,
   IntPtr SecurityDescriptor
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/windows/desktop/msmq/ms705190(v=vs.85))

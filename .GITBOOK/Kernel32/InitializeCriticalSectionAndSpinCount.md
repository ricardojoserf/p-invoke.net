## InitializeCriticalSectionAndSpinCount

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool InitializeCriticalSectionAndSpinCount(
   out CRITICAL_SECTION lpCriticalSection,
   uint dwSpinCount
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/synchapi/nf-synchapi-initializecriticalsectionandspincount)

## DdeUnregisterService

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool DdeUnregisterService(
   IntPtr idInst,
   IntPtr hszService
);
```


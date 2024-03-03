## DdeAbandonTransaction

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool DdeAbandonTransaction(
   uint idInst,
   IntPtr hConv,
   uint idTransaction
);
```


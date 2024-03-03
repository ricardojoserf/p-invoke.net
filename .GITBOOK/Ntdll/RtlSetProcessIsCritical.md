## RtlSetProcessIsCritical

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int RtlSetProcessIsCritical(
   bool NewValue,
   bool RestoreValue,
   bool* OldValue,
   uint Flags
);
```


## CoAllowSetForegroundWindow

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoAllowSetForegroundWindow(
   IUnknown pUnk,
   IntPtr lpvReserved
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/objbase/nf-objbase-coallowsetforegroundwindow)

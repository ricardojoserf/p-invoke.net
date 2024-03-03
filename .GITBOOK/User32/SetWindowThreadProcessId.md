## SetWindowThreadProcessId

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern uint SetWindowThreadProcessId(
   IntPtr hWnd,
   ref uint lpdwProcessId
);
```


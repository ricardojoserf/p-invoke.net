## CheckAppInitBlockedServiceIdentity

```csharp
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CheckAppInitBlockedServiceIdentity(
   IntPtr hAppID,
   ref IntPtr lpString
);
```


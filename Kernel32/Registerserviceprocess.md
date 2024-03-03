## Registerserviceprocess

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool RegisterServiceProcess(uint dwProcessId,
   uint dwServiceType
);
```


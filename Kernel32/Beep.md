## Beep

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool Beep(
   uint dwFreq,
   uint dwDuration
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/utilapiset/nf-utilapiset-beep)

## SaferCloseLevel

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SaferCloseLevel(
   IntPtr hLevelHandle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winsafer/nf-winsafer-safercloselevel)

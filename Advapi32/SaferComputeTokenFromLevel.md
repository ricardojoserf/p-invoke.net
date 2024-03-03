## SaferComputeTokenFromLevel

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SaferComputeTokenFromLevel(
   IntPtr LevelHandle,
   IntPtr InAccessToken,
   out IntPtr OutAccessToken,
   uint dwFlags,
   IntPtr lpReserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winsafer/nf-winsafer-safercomputetokenfromlevel)

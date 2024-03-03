## CoLockObjectExternal

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoLockObjectExternal(
   IUnknown pUnk,
   int fLock,
   int fLastUnlockReleases
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-colockobjectexternal)

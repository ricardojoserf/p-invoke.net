## CoFreeUnusedLibrariesEx

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern void CoFreeUnusedLibrariesEx(
   uint dwUnloadDelay,
   uint dwReserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cofreeunusedlibrariesex)

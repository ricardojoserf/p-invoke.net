## CoWaitForMultipleHandles

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoWaitForMultipleHandles(
   uint dwFlags,
   int dwTimeout,
   uint cHandles,
   IntPtr lphandles,
   out uint lpdwindex
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cowaitformultiplehandles)

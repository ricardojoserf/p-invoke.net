## CoCopyProxy

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoCopyProxy(
   IUnknown pProxy,
   out IUnknown ppCopy
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cocopyproxy)

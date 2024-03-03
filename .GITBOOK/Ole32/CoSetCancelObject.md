## CoSetCancelObject

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoSetCancelObject(
   IUnknown pUnk,
   IAsyncManager pAsyncManager
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cosetcancelobject)

## CoSwitchCallContext

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoSwitchCallContext(
   IUnknown pObject,
   out IUnknown ppOldObject
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-coswitchcallcontext)

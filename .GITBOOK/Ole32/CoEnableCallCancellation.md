## CoEnableCallCancellation

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoEnableCallCancellation(
   IUnknown punk,
   uint dwTimeout,
   uint dwCancelTimeout
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-coenablecallcancellation)

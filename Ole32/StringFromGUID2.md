## StringFromGUID2

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StringFromGUID2(
   ref Guid rguid,
   [MarshalAs(UnmanagedType.LPWStr)] out string lpsz,
   int cchMax
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-stringfromguid2)

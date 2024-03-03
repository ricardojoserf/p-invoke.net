## IIDFromString

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int IIDFromString(
   [MarshalAs(UnmanagedType.LPWStr)] string lpsz,
   out Guid lpiid
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-iidfromstring)

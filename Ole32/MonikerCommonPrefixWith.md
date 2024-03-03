## MonikerCommonPrefixWith

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int MonikerCommonPrefixWith(
   IMoniker pmkThis,
   IMoniker pmkOther,
   out IMoniker ppmkCommon
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/objbase/nf-objbase-monikercommonprefixwith)

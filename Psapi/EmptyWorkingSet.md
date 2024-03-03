## EmptyWorkingSet

```csharp
[DllImport("psapi.dll", SetLastError = true)]
public static extern bool EmptyWorkingSet(
   IntPtr hProcess
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/psapi/nf-psapi-emptyworkingset)

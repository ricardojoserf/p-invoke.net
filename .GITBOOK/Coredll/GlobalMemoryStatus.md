## GlobalMemoryStatus

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern void GlobalMemoryStatus(
   ref MEMORYSTATUS lpBuffer
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-globalmemorystatus)

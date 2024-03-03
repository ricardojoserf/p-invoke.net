## MiniDumpWriteDump

```csharp
[DllImport("Dbghelp.dll", SetLastError = true)]
public static extern bool MiniDumpWriteDump(
   IntPtr hProcess,
   uint ProcessId,
   SafeHandle hFile,
   int DumpType,
   ref MINIDUMP_EXCEPTION_INFORMATION ExceptionParam,
   IntPtr UserStreamParam,
   IntPtr CallbackParam
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/minidumpapiset/nf-minidumpapiset-minidumpwritedump)

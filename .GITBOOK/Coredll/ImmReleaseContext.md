## ImmReleaseContext

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool ImmReleaseContext(
   IntPtr hwnd,
   IntPtr himc
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/imm/nf-imm-immreleasecontext)

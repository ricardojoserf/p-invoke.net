## SetAbortProc

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int SetAbortProc(
   IntPtr hdc,
   [MarshalAs(UnmanagedType.FunctionPtr)] ABORTPROC lpAbortProc
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setabortproc)

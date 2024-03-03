## BatchExec

```csharp
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int BatchExec(
   IntPtr hwndOwner,
   string lpszCmdline,
   int dwCmdexecopt,
   ref string lpszOut,
   int lpszOutSize
);
```


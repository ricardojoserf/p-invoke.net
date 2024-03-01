## CommandLineToArgvW

```
[DllImport("shell32.dll")]
public static extern IntPtr CommandLineToArgvW(
   [MarshalAs(
   UnmanagedType.LPWStr)] string lpCmdLine,
   out int pNumArgs
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-commandlinetoargvw)

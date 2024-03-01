## FreeLibraryAndExitThread

```
[DllImport("kernel32.dll", SetLastError = true)]
public static extern void FreeLibraryAndExitThread(
   IntPtr hLibModule,
   uint dwExitCode
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-freelibraryandexitthread)

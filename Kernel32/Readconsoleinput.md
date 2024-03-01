## Readconsoleinput

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ReadConsoleInput(IntPtr hConsoleInput,
   [Out] INPUT_RECORD[] lpBuffer,
   uint nLength,
   out uint lpNumberOfEventsRead
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/readconsoleinput)

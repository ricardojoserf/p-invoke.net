## Writeconsoleinput

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool WriteConsoleInput(
   IntPtr hConsoleInput,
   INPUT_RECORD[] lpBuffer,
   uint nLength,
   out uint lpNumberOfEventsWritten
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/console/writeconsoleinput)

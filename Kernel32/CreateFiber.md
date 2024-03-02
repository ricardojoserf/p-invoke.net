## CreateFiber

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr CreateFiber(
   int dwStackSize,
   LPFIBER_START_ROUTINE lpStartAddress,
   IntPtr lpParameter
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/procthread/using-fibers#:~:text=The%20CreateFiber%20function%20creates%20a,of%20a%20user%2Dsupplied%20function.)

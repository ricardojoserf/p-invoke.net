## EapHostPeerInvokeConfigUI

```csharp
[DllImport("wlanapi.dll", SetLastError = true)]
public static extern uint EapHostPeerInvokeConfigUI(
   [MarshalAs(UnmanagedType.LPWStr)] string profileName,
   IntPtr parentWindow,
   IntPtr pEapMethodInputData,
   IntPtr pEapMethodOutputData,
   IntPtr pReserved
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/eaphostpeerconfigapis/nf-eaphostpeerconfigapis-eaphostpeerinvokeconfigui)

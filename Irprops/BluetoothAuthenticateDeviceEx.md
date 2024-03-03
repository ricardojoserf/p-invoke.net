## BluetoothAuthenticateDeviceEx

```csharp
[DllImport("Irprops.dll", SetLastError = true)]
public static extern uint BluetoothAuthenticateDeviceEx(
   IntPtr hwndParentIn,
   IntPtr hRadioIn,
   ref BLUETOOTH_DEVICE_INFO pbtdiInout,
   IntPtr pszPasskey,
   uint ulPasskeyRequirement
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/bluetoothapis/nf-bluetoothapis-bluetoothauthenticatedeviceex)

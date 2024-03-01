## BluetoothAuthenticateDevice

```
[DllImport("Irprops.dll", SetLastError = true)]
public static extern uint BluetoothAuthenticateDevice(
   IntPtr hRadio,
   IntPtr hDevice,
   ref BLUETOOTH_DEVICE_INFO pbtbi,
   IntPtr pszPasskey,
   uint ulPasskeyRequirement
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/bluetoothapis/nf-bluetoothapis-bluetoothauthenticatedevice)

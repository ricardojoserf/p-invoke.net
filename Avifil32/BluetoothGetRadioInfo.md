## BluetoothGetRadioInfo

```
[DllImport("BluetoothApis.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool BluetoothGetRadioInfo(
   IntPtr hRadio,
   ref BLUETOOTH_RADIO_INFO pRadioInfo
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/bluetoothapis/nf-bluetoothapis-bluetoothgetradioinfo)

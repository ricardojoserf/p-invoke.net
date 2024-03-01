## BluetoothFindFirstRadio

```
[DllImport("Irprops.dll", SetLastError = true)]
public static extern IntPtr BluetoothFindFirstRadio(
   ref BLUETOOTH_FIND_RADIO_PARAMS pbtfrp,
   out IntPtr phRadio
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/bluetoothapis/nf-bluetoothapis-bluetoothfindfirstradio)

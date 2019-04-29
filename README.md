# DPBlue
A simple lite library for bluetooth spp

# Communicate with a bluetooth device just like:

````
BluetoothSelector.select(context, new BluetoothSelector.Callback() {
    @Override
    public void onDeviceSelected(BlueDevice device) {
        Blue blue = Blue.get(device,uuid);
//      blue.setFactory();
//      blue.setGlobalCallback();
//      blue.send(bytes);
//      blue.send();
    }
});
````

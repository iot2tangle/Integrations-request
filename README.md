# I2T Integration Requests

If you have code to integrate an IoT device with IOTA Streams and you think it could be of value, [**submit an issue on this repo***](https://github.com/iot2tangle/integrations/issues) linking to the code and explaining how to test it. 

Keep in mind that your work will have to meet two conditions:

- Easy step by step guide Readme 
- Use the I2T Json Standard

## Our Json Standard

Our Rust Gateway will listen and publish to the Tangle via Streams any IoT device data as long as it uses 
the I2T Json Standard. 

```
{"iot2tangle":[{"sensor": "Environmental","data":[{"Pressure":"102033"},{"Temp":"26160"},{"Humidity":"33"}]},{"sensor":"Accel","data":[{"x":"9"},{"y":"12"},{"z":"1009"}]},{"sensor":"Gyroscope","data":[{"x":"122"},{"y":"1708"},{"z":"5246"}]},{"sensor":"Inertial","data":[{"x":"183"},{"y":"122"},{"z":"-915"}]},{"sensor":"Light","data":[{"milliLux":"192960"}]},{"sensor":"Magnetometer","data":[{"x":"-59"},{"y":"3"},{"z":"7"}]},{"sensor":"Acoustic","data":[{"mp":"0.004649"}]} ],"device": "YOUR-DEVICE","timestamp": "1601653408"}
```


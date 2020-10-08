# Add your integration to the I2T Hub

If you have code to integrate an IoT device with IOTA Streams and you think it could be of value, [**submit an issue here**](https://github.com/iot2tangle/integrations/issues) linking to the code and explaining how to test it. 

Keep in mind that your work will have to meet two conditions:

- Easy step by step guide Readme 
- Use the I2T Json Standard

## Our Json Standard

Our Rust Gateway will listen and publish to the Tangle via Streams any IoT device sending data as long as it uses 
the **I2T Json Standard**. 

```
{"iot2tangle":[{"sensor": "Environmental","data":[{"Pressure":"102033"},{"Temp":"26160"},{"Humidity":"33"}]},{"sensor":"Accel","data":[{"x":"9"},{"y":"12"},{"z":"1009"}]},{"sensor":"Gyroscope","data":[{"x":"122"},{"y":"1708"},{"z":"5246"}]},{"sensor":"Inertial","data":[{"x":"183"},{"y":"122"},{"z":"-915"}]},{"sensor":"Light","data":[{"milliLux":"192960"}]},{"sensor":"Magnetometer","data":[{"x":"-59"},{"y":"3"},{"z":"7"}]},{"sensor":"Acoustic","data":[{"mp":"0.004649"}]} ],"device": "YOUR-DEVICE","timestamp": "1601653408"}
```

## How does the sharing my integration process works?

If your work is of value, we will create a repository at our Hub and provide you with the permissions so you can mantain it over the time. You can use your project logo, link to your web and mention your original work. We just provide you with a repo so your work lives in our Hub ;)

## I have the IoT device end solved but I don't know anything about DLTs

Request an integration! We can help you to bridge your work with IOTA.






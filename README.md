# Mule4-base64-manipulation


Mule binary module let's us to convert your everyday PDF or image file to base64 strings.

You can store these base64 values as a regular text in any database of your choice.

This type of conversion reduces the network overhead that is required to fetch images or other pdf's over a network.

For images, you render these base64 strings at client side. Which can help in decreasing the TTF(Time to fetch) resources saving a great of time on page loading times.

## Requirements
Anypoint studio 7+
Mule runtime 4.0+

## Installation

Just clone this project and import into your anypoint studio.

## References
https://docs.mulesoft.com/mule-runtime/4.2/dw-binaries

Endpoints:
~~~
http://localhost:8082/api/convert-image-to-base64
http://localhost:8082/api/convert-base64-to-image
http://localhost:8082/api/convert-pdf-to-base64
http://localhost:8082/api/convert-base64-to-pdf
~~~

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.


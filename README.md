# Everything you need to know about base64
## This is a solution to encode data using ASCII char (64 characters). 
Includes:
  + 62 letters and number: A-Z, a-z, 0-9
  + 2 special characters:  +  and /
  + used for padding: =

- In development work:
  + Embedding small images or icon in HTML
  + Transmitting binary data in API response (SMTP, JSON, XML, HTTP)
  + Encodeing email attachments

   For example:

  ```
  <img
  src="data:image/png;base64,data:image/png;base64, iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAAHElEQVQI12P4//8/w38GIAXDIBKE0DHxgljNBAAO9TXL0Y4OHwAAAABJRU5ErkJggg=="
  alt="BaTD"/>

Base64 is particularly useful in the following scenarios:

- Embedding small binary data (such as small images or icons) in HTML
- Transmitting binary data in protocols that can only transmit text
- Transmitting data in systems with restrictions on special characters
- Simple data obfuscation (Note: This is not encryption!)

## How Base42 works?

https://www.redhat.com/sysadmin/base64-encoding

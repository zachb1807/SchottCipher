# SchottCipher

An encryption cipher created by Jack Schott that I converted into a working Java library.

## Implementation

To implement the cipher in your program, download the JAR file [from the releases page](https://github.com/zachb1807/SchottCipher/releases) and add it to your Java classpath.

Alternatively, you can clone the code and build the JAR yourself:

```
git clone https://github.com/coobird/thumbnailator.git
```

## Usage
The following demonstrates a few of the functions that SchottCipher offers:
```java
import schottcipher.SchottCipher;

SchottCipher cipher = new SchottCipher();

// Returns the encryption for message 'words'
cipher.encryptMessage('words');

// Returns the decrypted message
cipher.decryptMessage('257.917,100.000,14.000,11.000,-7.842,-4616.000');
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

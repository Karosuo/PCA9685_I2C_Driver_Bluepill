# PCA9685_I2C_Driver_Bluepill
STM32F103C (Bluepill) I2C driver header files, register addresses, command strings and functions required to interact with the PCA9685 PWM Driver

### Prerequisites

The STM32CubeIDE code generator feature was used to enable the I2C 1 output to ...
This peripheral configuration and startup is required to use the library
```C
static void MX_I2C1_Init(void);
```

### Installing

As long as the pca9685_driver.h and pca9685_driver.c files are in the include directory and the prerquisites are met, the functions will be accesible with a regular include:
```
#include <pca9685_driver.h>
```
If the files are in the main.c file directory, then use the double quote notation

```
#include "pca9685_driver.h"
```

## Built With

* [STM32CubeIDE](https://www.st.com/en/development-tools/stm32cubeide.html) - The STMicro IDE with the CubeMX code autogeneration tool 
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

We still don't have a structure to accept contributing, but we're going to base ourselfs on the following template.
If for any reason you find this snipped useful and want to modify it, please by all means do so, and send us a pull request.
[CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426)

## Versioning

This is a short snippet of code, but we're going to try to follow [SemVer](http://semver.org/)

## Authors

* [**Rafael Karosuo**](https://www.linkedin.com/in/rafaelkarosuo/) - *CoDe Pretzel*
* [**Hermann Leonides**](https://www.linkedin.com/in/hermann-leonides-83a4801a1/) - *CoDe Pretzel*

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

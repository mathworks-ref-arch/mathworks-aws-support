# MathWorks® interfaces for Amazon Web Services™ (AWS)
Source code, documentation and reference material supporting MathWorks products on Amazon Web Services.

## System Requirements:
MathWorks Products (http://www.mathworks.com)

1. [MATLAB®](https://www.mathworks.com/products/matlab.html) (R2017a or later)
2. [MATLAB Compiler™](https://www.mathworks.com/products/compiler.html) and [MATLAB Compiler SDK™](https://www.mathworks.com/products/matlab-compiler-sdk.html) (R2017a or later)
3. [MATLAB Production Server™](https://www.mathworks.com/products/matlab-production-server.html) (R2017a or later)
4. [MATLAB Distributed Computing Server™](https://www.mathworks.com/products/distriben.html) (R2017a or later)

Amazon Products (http://www.amazonaws.com)

1. Amazon Web Services account
2. [AWS SDK for Java](https://aws.amazon.com/sdk-for-java/) (version 1.11.367 or later)

Please note that some of the components included in this repository may require
different versions that supercede these requirements.

## Getting Started
Clone this repository using the recursive flag.
```
git clone --recursive https://github.com/mathworks-ref-arch/mathworks-aws-support.git
```

Rebuild any required java components using:

```bash
mvn clean package
```
On any POM.xml files in this or dependent repositories.

Please refer to the [Documentation](Documentation/README.md) to get started.

## License
The License agreement for this software can be found [here](LICENSE.TXT).    

## Enhancement Request
Provide suggestions for additional features or capabilities using the following link:   
https://www.mathworks.com/products/reference-architectures/request-new-reference-architectures.html

## Support
Email: `mwlab@mathworks.com` or please log an issue    

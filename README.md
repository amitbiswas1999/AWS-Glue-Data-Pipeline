### Project Architecture
![Screenshot from 2023-04-05 10-26-35](https://user-images.githubusercontent.com/88819794/229986080-6b3dcfe8-ee73-4b41-b042-433d2d132e61.png)





To create zip file for aws lambda function 

use below commadn

```commandline
pip install --platform manylinux2014_x86_64 --target=<folder_name> --implementation cp --python 3.9 --only-binary=:all: --upgrade <lib1> <lib2>
```

```
pip install --platform manylinux2014_x86_64 --target=lambda_function_code --implementation cp --python 3.9 --only-binary=:all: --upgrade pymongo[srv] requests boto3
```

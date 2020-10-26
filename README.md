# GaussJordanEliminate

Gaussian elimination, also known as row reduction, is an algorithm in linear algebra for solving a system of linear equations. It is usually understood as a sequence of operations performed on the corresponding matrix of coefficients. This method can also be used to find the rank of a matrix, to calculate the determinant of a matrix, and to calculate the inverse of an invertible square matrix. 

[See Wikipedia](https://en.wikipedia.org/wiki/Gaussian_elimination)

## Usage

```java
int[][] matrix = {{2,1,-1,8},
                  {-3,-1,2,-11},
                  {-2,1,2,-3}};

matrix = GaussJordanEliminate.solve(matrix);
System.out.println(Arrays.toString(GaussJordanEliminate.extractAnswers(matrix)));
```

![Image](https://wikimedia.org/api/rest_v1/media/math/render/svg/143d91265d57a1d2bd91ef95aec9f2e466ba411b) : ![Image](https://wikimedia.org/api/rest_v1/media/math/render/svg/158d23387edac419ba2e00a3b6bcf0f400779f2c)

Logs :
```
Input : 
    [2, 1, -1, 8],
    [-3, -1, 2, -11],
    [-2, 1, 2, -3]
    
Start : 
    [2, 1, -1, 8],
    [0, 1, 1, 2],
    [0, 0, 1, -1]
    
Output : 
    [1, 0, 0, 2],
    [0, 1, 0, 3],
    [0, 0, 1, -1]

Answers :
    [2, 3, -1]
```

## Author 
- **Amir Hossein Aghajari**

License
=======

    Copyright 2020 Amir Hossein Aghajari
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

<br><br>
<div align="center">
  <img width="64" alt="LCoders | AmirHosseinAghajari" src="https://user-images.githubusercontent.com/30867537/90538314-a0a79200-e193-11ea-8d90-0a3576e28a18.png">
  <br><a>Amir Hossein Aghajari</a> • <a href="mailto:amirhossein.aghajari.82@gmail.com">Email</a> • <a href="https://github.com/Aghajari">GitHub</a>
</div>

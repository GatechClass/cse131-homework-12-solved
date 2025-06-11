# cse131-homework-12-solved
**TO GET THIS SOLUTION VISIT:** [CSE131 Homework #12 Solved](https://mantutor.com/product/cse131-homework-12-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116000&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE131 Homework #12 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
Objective :

Learn how to use file input and output, strings, and functions.

12.

Convolutional Neural Networks (CNNs) are a type of feedforward neural network that excels in machine learning tasks involving large images. A critical component of CNNs is the 2-D Convolution layer, which uses the weights in the kernel to perform convolution operations with the data input from the previous layer, and then passes the result through an activation function to produce the output for that layer.

Please design a program to implement 2-D Convolution with the following requirements:

First, please write a function use srand(5) as the seed to generate a random number matrix (16×16) with values ranging from -10 to +10, and output it as “Matrix.txt”. Additionally, output a bias matrix (14×14) where all elements are 1, named “Bias.txt”. Print and output both matrices.

Second, write a function to use the previously generated random number matrix and bias, along with the provided “kernel.txt” file, to perform convolution operations. The process for matrix convolution operation is as follows:

Taking the above figure as an example, the calculation process of convolution operation is as follows:

2*1 + 4*2 + 9*3 + 2*(-4) + 1*7 + 4*4 + 1*2 + 1*(-5) + 2*1 = 51

4*1 + 9*2 + 1*3 + 1*(-4) + 4*7 + 4*4 + 1*2 + 2*(-5) + 9*1 = 66

9*1 + 1*2 + 4*3 + 4*(-4) + 4*7 + 6*4 + 2*2 + 9*(-5) + 2*1 = 20 2*1 + 1*2 + 4*3 + 1*(-4) + 1*7 + 2*4 + 7*2 + 3*(-5) + 5*1 = 31

…

2*1 + 9*2 + 2*3 + 5*(-4) + 1*7 + 3*4 + 4*2 + 8*(-5) + 5*1 = -2

After the operation, write a function add the bias to get a 14×14 matrix, print it out, and output it as “Conv.txt”.

Process the output from point 2 through the ReLU activation function (ReLU(y) = max(0, x)), and print and output the result as “Result.txt”.

Hint:

The files you need to submit are “Matrix.txt”, “Conv.txt”, “Result.txt”, and the .c file for the question.

The output of the convolution operation should be rounded to the nearest integer. For example, 1.50 rounds up to 2, and 1.49 rounds down to 1.

ReLU is a function that zeroes out negative values, meaning it retains positive values as is and converts negative values to 0.

The names of the functions are generate() and convolutional( ) and relu( ) respectively.

Output :

繳交格式及規定 : 程式重點地方請加註解,給分也會酌量參考註解。

請繳交 .c 檔即可。

c 檔的檔名一律統一,以學號為檔名壓縮成一個以學號為名的壓縮檔

上傳,

上傳請一律繳交壓縮檔。

Example: 若學號為 B123456789, 則.c/.cpp 檔名為 B123456789.c , 而壓縮檔名為 B123456789.rar。

無輸入輸出及逾期者一律以 0 分計算。

作業請上傳中山網路大學 網大上傳方式:

1. 點選要繳交的作業,選擇「進行作業」。

2. 依照流程上傳檔案。

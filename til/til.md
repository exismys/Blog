## 2025-09-08
**Overloading [] operator in C++:** two varients, `double& operator[](int i);` and `double operator[](int i) const;`. First one returns a reference to actual data member to which we can assign some value. Second one only works when called on a const object and returns just a value. Makes sense, can't assign a value to a value.

**Configuring C++ code run in VS code:** I was facing an issue with running C++ code in VS code through code run button because it was using `gcc` as a compiler. I could change this in `.vscode/tasks.json` to use `g++` instead.

Of course, I had to modify `.gitignore` after to ignore all `.vscode` except that one specific file.

`.gitignore` entry:
`.vscode/*`
`!.vscode/tasks.json`

## 2025-09-07
**URL Hash based routing:** This is actually very interesting, saves you load time switching between pages.

**Sine Wave Sampling:** Wrote a blog about producing sounds programmatically. More info here: [sine wave sampling](https://github.com/exismys/Blog/blob/main/blogs/2025-09-07-sine-wave-sampling.md)

## 2025-09-06
**Latex Rendering in Markdown:** I learnt how to sprinkle latex code in markdown for stuff like math equations. $...$ for inline and $$...$$ for multiline. My first use here: [sine wave sampling](https://github.com/exismys/Blog/blob/main/blogs/2025-09-07-sine-wave-sampling.md)

## 2025-09-03
**Matrices as Linear Transformation:** of vector space. Every matrix represents a linear transformation. A matrix *A* takes a vector *V* as an input and transforms into a vector *V'*. I am thinking of writing a blog on this.

## 2025-08-25
**PPM:** So, an image is just a text file with color data? .ppm image format is just a list of C * R colors. Check out [a sample C++ code which prints .ppm fomrat](https://github.com/exismys/HelloWorld/blob/master/cpp/audio-and-graphics/image.cpp). Save the output in a file with `./app.out > image.ppm` and you should be able to open it with any image viewer (unless you are using windows, then good luck). 

Download Link: https://assignmentchef.com/product/solved-cs204-homework-4-constructors-and-operator-overloading
<br>
<strong>Introduction </strong>

<strong> </strong>This homework’s aim is to make you familiar with the fundamentals of Object-Oriented Programming: <strong>constructors</strong>, <strong>destructors</strong> and <strong>operator overloading</strong>. You will be given a sorted linked list class which you will be asked to create constructor, destructor and overload some operators.







Along with the PDF document, you are given a header file <strong>SortedArray.h</strong> and a corresponding cpp file <strong>SortedArray.cpp</strong>. Also another cpp file is supplied to you named <strong>Test.cpp</strong> for testing your code. You will be editing SortedArray.h and SortedArray.cpp files. You won’t be editing the Test.cpp file. Also output of the Test.cpp will be given so that you can check your code works correctly.




You need to implement <strong>(deep)</strong> <strong>copy</strong> <strong>constructor</strong> and <strong>destructor</strong> for SortedArray class. There are some comments in the given header and cpp files, use them as guidelines. You will also need to overload <strong>assignment</strong> (=) and <strong>plus</strong> (+) operators. After you implement copy constructor, destructor, assignment and addition operators, you should be able to do the following example operations.




SortedArray a2, a3, a4;

SortedArray a1(a2); // copy constructor

a4 = a1 + a2 + a3; // sorted arrays will be merged and result will also be sorted a1 = a1 + 10; // new integer value (in this case 10) will be inserted to sorted array  a2 = 5 + a1; // new integer value (in this case 5) will be inserted to sorted array a1 = a2 = a3; //cascading assignment




<strong>Output </strong>

Output of the Test.cpp is given in the following image, which is also provided in the output.txt file.




<h2>Some Important Rules</h2>

In order to get a full credit, your programs must be efficient and well presented, presence of any redundant computation or bad indentation, or missing, irrelevant comments are going to decrease your grades. You also have to use understandable identifier names, informative introduction and prompts. Modularity is also important; you have to use functions wherever needed and appropriate.




When we grade your homeworks we pay attention to these issues. Moreover, in order to observe the real performance of your codes, we are going to run your programs in <em>Release</em> mode and <strong>we may test your programs with very large test cases</strong>.




<strong> </strong>

<strong>What and where to submit (PLEASE READ, IMPORTANT) </strong>

You should prepare (or at least test) your program using MS Visual Studio 2012 C++. We will use the standard C++ compiler and libraries of the abovementioned platform while testing your homework. It’d be a good idea to write your name and last name in the program (as a comment line of course).




Submissions guidelines are below. Some parts of the grading process are automatic. Students are expected to strictly follow these guidelines in order to have a smooth grading process. If you do not follow these guidelines, depending on the severity of the problem created during the grading process, 5 or more penalty points are to be deducted from the grade. Name your cpp file that contains your program as follows:




<strong><em>“SUCourseUserName_YourLastname_YourName_HWnumber.cpp” </em></strong>




Your SUCourse user name is actually your SUNet username that is used for checking sabanciuniv e-mails. Do NOT use any spaces, non-ASCII and Turkish characters in the file name. For example, if your SUCourse user name is valent, name is Valentina, and last name is Tereşkova, then the file name must be:




<h2>Valent_Tereskova_Valentina_hw1.cpp</h2>




Do not add any other character or phrase to the file name. Make sure that this file is the latest version of your homework program. Compress this cpp file using WINZIP or WINRAR programs. Please use “zip” compression. “rar” or another compression mechanism is NOT allowed. Our homework processing system works only with zip files. Therefore, make sure that the resulting compressed file has a zip extension. Check that your compressed file opens up correctly and it contains your cpp file.




You will receive no credits if your compressed zip file does not expand or it does not contain the correct file. The naming convention of the zip file is the same as the cpp file (except the extension of the file of course). The name of the zip file should be as follows:



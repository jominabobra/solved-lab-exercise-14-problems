Download Link: https://assignmentchef.com/product/solved-lab-exercise-14-problems
<br>
<ol>

 <li>Write C++ programs</li>

 <li>Compile C++ programs</li>

 <li>Implement programs that use templates and vectors</li>

</ol>

<h1><a id="user-content-additional-reading" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14#additional-reading" aria-hidden="true"></a>Additional Reading</h1>

This lab exercise requires an understanding of some concepts to solve the problems. You are strongly encouraged to read the following tutorials to help you answer the problems.

<ol>

 <li><a href="https://github.com/ILXL-guides/function-file-organization">Organizing C++ files: function prototypes, implementations, and drivers</a>.</li>

 <li><a href="https://github.com/ILXL-guides/object-parameters-and-return-values">Using objects as parameters and return values in functions</a></li>

 <li><a href="https://github.com/ILXL-guides/arrays-as-parameters">Passing arrays as parameters to functions</a></li>

 <li><a href="https://github.com/ILXL-guides/cpp-file-io">File reading and writing (also includes dealing with arrays)</a></li>

</ol>

<h1><a id="user-content-instructions" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14#instructions" aria-hidden="true"></a>Instructions</h1>

Answer the programming problems sequentially (i.e., answer prob01 before prob02). If you have questions let your instructor or the lab assistant know. You can also consult your classmates.

When you answer two programming problems correctly, let your instructor know and wait for further instruction.

<h1><a id="user-content-lab-exercise-guide" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14#lab-exercise-guide" aria-hidden="true"></a>Lab exercise guide</h1>

Here’s a link to the <a href="https://docs.google.com/document/d/1EX01EtrO-pkHNLVPxiq7HNh1f5KnJZnr_dlJcO4T7t0/edit?usp=sharing" rel="nofollow">Lab exercise guide</a> in case you need to review the lab exercise objectives, grading scheme, or evaluation process.

<h1>Pair Template</h1>

In this program, you will be creating a class that utilizes class templates.

<h2><a id="user-content-mypair-template-class" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob01#mypair-template-class" aria-hidden="true"></a>MyPair Template Class</h2>

Create a class called <code>MyPair</code> that uses <code>template &lt;class T&gt;</code> and will have the following:

<h3><a id="user-content-private-member-variables" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob01#private-member-variables" aria-hidden="true"></a>Private Member Variables</h3>

<ol>

 <li><code>value1_</code> which is a <code>T</code> object.</li>

 <li><code>value2_</code> which is a <code>T</code> object.</li>

</ol>

<h3><a id="user-content-non-default-constructor" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob01#non-default-constructor" aria-hidden="true"></a>Non-Default Constructor</h3>

Create a non-default constructor that takes in two <code>T</code> objects as parameters and initializes the values to the data member variables respectively.

<h3><a id="user-content-accessors" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob01#accessors" aria-hidden="true"></a>Accessors</h3>

Create accessors for both data members

<h3><a id="user-content-display-member-function" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob01#display-member-function" aria-hidden="true"></a>Display Member Function</h3>

Create a member function called <code>display()</code> that will display the member variables in the order shown in the output below.

<pre><code>[Value1, Value2]</code></pre>

<h3><a id="user-content-display-reverse-member-function" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob01#display-reverse-member-function" aria-hidden="true"></a>Display Reverse Member Function</h3>

Create a member function called <code>display_reverse()</code> that will display the member variables in reverse order as shown in the output below.

<pre><code>[Value2, Value1]</code></pre>

<h3><a id="user-content-max-value-member-function" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob01#max-value-member-function" aria-hidden="true"></a>Max Value Member Function</h3>

Create a member function called <code>max_value()</code> that will return a <code>T</code> object. This member function should compare the two member variable values and return the greater value (if the values are equal, return the second value).

<h3><a id="user-content-min-value-member-function" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob01#min-value-member-function" aria-hidden="true"></a>Min Value Member Function</h3>

Create a member function called <code>min_value()</code> that will return a <code>T</code> object. This member function should compare the two member variable values and return the lesser value (if the values are equal, return the second value).

<h3><a id="user-content-swap-value-member-function" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob01#swap-value-member-function" aria-hidden="true"></a>Swap Value Member Function</h3>

Create a member function called <code>swap_value()</code> that will swap the two member variable values.

<h2><a id="user-content-other-instructions" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob01#other-instructions" aria-hidden="true"></a>Other instructions</h2>

Complete the <code>main</code> function as described. Place your classes in <code>pair_class_template.hpp</code>. Member functions that take more than five lines or use complex constructs should have their function prototype in <code>pair_class_template.hpp</code> and implementation in <code>pair_class_template.cpp</code>.

<h1><a id="user-content-sample-output" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob01#sample-output" aria-hidden="true"></a>Sample Output</h1>

<pre><code>[3, 5][5, 3]53[5, 3][3, 5][9.7, 6.4][6.4, 9.7]9.76.4[6.4, 9.7][9.7, 6.4][a, z][z, a]za[z, a][a, z]</code></pre>

<h1><a id="user-content-submission-checklist" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob01#submission-checklist" aria-hidden="true"></a>Submission checklist</h1>

<ol>

 <li>Created function prototype and stored in <code>.hpp</code> file.</li>

 <li>Created function implementation and stored in <code>.cpp</code> file (see <a href="https://github.com/ILXL-guides/function-file-organization">reference</a>).</li>

 <li>Call function in the driver</li>

 <li>Compiled and ran the driver (<code>main</code>).</li>

 <li>Manually checked for compilation and logical errors.</li>

 <li>Ensured no errors on the unit test (<code>make test</code>).</li>

 <li>Followed advice from the stylechecker (<code>make stylecheck</code>).</li>

 <li>Followed advice from the formatchecker to improve code readbility (<code>make formatcheck</code>).</li>

</ol>

<h1><a id="user-content-code-evaluation" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob01#code-evaluation" aria-hidden="true"></a>Code evaluation</h1>

Open the terminal and navigate to the folder that contains this exercise. Assuming you have pulled the code inside of <code>/home/student/labex02-tuffy</code> and you are currently in <code>/home/student</code> you can issue the following commands

<pre><code>cd labex02-tuffy</code></pre>

You also need to navigate into the problem you want to answer. To access the files needed to answer problem 1, for example, you need to issue the following command.

<pre><code>cd prob01</code></pre>

When you want to answer another problem, you need to go back up to the parent folder and navigate into the next problem. Assuming you are currently in <code>prob01</code>, you can issue the following commands to go to the parent folder then go into another problem you want to answer; <code>prob02</code> for example.

<pre><code>cd ..cd prob02</code></pre>

Use the <code>clang++</code> command to compile your code and the <code>./</code> command to run it. The sample code below shows how you would compile code saved in <code>pair_class_template.cpp</code> and <code>main.cpp</code>, and into the executable file <code>main</code>. Make sure you use the correct filenames required in this problem. Take note that if you make any changes to your code, you will need to compile it first before you see changes when running it.

<pre><code>clang++ -std=c++17 main.cpp pair_class_template.cpp -o main./main</code></pre>

You can run one, two, or all the commands below to <code>test</code> your code, <code>stylecheck</code> your code’s design, or <code>formatcheck</code> your work. Kindly make sure that you have compiled and executed your code before issuing any of the commands below to avoid errors.

<pre><code>make testmake stylecheckmake formatcheck</code></pre>

A faster way of running all these tests uses the <code>all</code> parameter.

<h6><code>make all</code></h6>

<h1>Statistics Calculator</h1>

In this program, you will be using the <code>vector</code> library.

<h2><a id="user-content-statistics-calculator-class" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob02#statistics-calculator-class" aria-hidden="true"></a>Statistics Calculator Class</h2>

Create a class called <code>StatisticsCalculator</code> that will have the following:

<h3><a id="user-content-data-members" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob02#data-members" aria-hidden="true"></a>Data members</h3>

<ol>

 <li><code>data_set_</code> that is an <code>std::vector</code> that contains <code>double</code> values. <code>std::vector</code> uses templates so we specify the type <code>double</code> inside the <code>&lt; &gt;</code>.</li>

</ol>

<h3><a id="user-content-member-functions" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob02#member-functions" aria-hidden="true"></a>Member functions</h3>

<h3><a id="user-content-add_data" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob02#add_data" aria-hidden="true"></a>add_data</h3>

Create a member function called <code>add_data</code> that takes 1 parameter, a <code>double</code> that will be stored in the vector. Use the <code>std::vector</code> member function <code>push_back</code> to store the data passed through the parameter into the vector.

<h3><a id="user-content-data_at" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob02#data_at" aria-hidden="true"></a>data_at</h3>

Create a member function called <code>data_at</code> that takes 1 parameter, an <code>int</code> that will be the index. This function should return the the element from the vector at the index using the index operator (<code>[ ]</code>).

<h3><a id="user-content-size_of_data" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob02#size_of_data" aria-hidden="true"></a>size_of_data</h3>

Create a member function called <code>size_of_data</code> that should return the size of the vector using the <code>std::vector</code> member function <code>size</code>.

<h3><a id="user-content-mean" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob02#mean" aria-hidden="true"></a>mean</h3>

Create a member function called <code>mean</code> that should return the mean of all the elements in the vector. If the vector is empty return a value of <code>0</code>. You can use <code>std::vector</code>‘s member function <code>empty()</code> to check.

<h2><a id="user-content-other-instructions" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob02#other-instructions" aria-hidden="true"></a>Other instructions</h2>

Complete the <code>main</code> function as described. Place your classes in <code>statistics_calculator.hpp</code>. Member functions that take more than five lines or use complex constructs should have their function prototype in <code>statistics_calculator.hpp</code> and implementation in <code>statistics_calculator.cpp</code>.

<h1><a id="user-content-sample-output-1" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob02#sample-output-1" aria-hidden="true"></a>Sample output 1</h1>

<pre>Welcome to the Statistics Calculator!Please select a menu option:1 - Add to the data set2 - Display the entire data set3 - Get the mean of the data set0 - Exit the programSelection: <b>1</b>Input the number you want to add to the data set: <b>23</b>Welcome to the Statistics Calculator!Please select a menu option:1 - Add to the data set2 - Display the entire data set3 - Get the mean of the data set0 - Exit the programSelection: <b>2</b>The data set0: 23Welcome to the Statistics Calculator!Please select a menu option:1 - Add to the data set2 - Display the entire data set3 - Get the mean of the data set0 - Exit the programSelection: <b>3</b>The mean of the data is 23.00Welcome to the Statistics Calculator!Please select a menu option:1 - Add to the data set2 - Display the entire data set3 - Get the mean of the data set0 - Exit the programSelection: <b>0</b>Exiting...</pre>

<h1><a id="user-content-sample-output-2" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob02#sample-output-2" aria-hidden="true"></a>Sample output 2</h1>

<pre>Welcome to the Statistics Calculator!Please select a menu option:1 - Add to the data set2 - Display the entire data set3 - Get the mean of the data set0 - Exit the programSelection: <b>2</b>The data setWelcome to the Statistics Calculator!Please select a menu option:1 - Add to the data set2 - Display the entire data set3 - Get the mean of the data set0 - Exit the programSelection: <b>3</b>The mean of the data is 0.00Welcome to the Statistics Calculator!Please select a menu option:1 - Add to the data set2 - Display the entire data set3 - Get the mean of the data set0 - Exit the programSelection: <b>0</b>Exiting...</pre>

<h1><a id="user-content-submission-checklist" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob02#submission-checklist" aria-hidden="true"></a>Submission checklist</h1>

<ol>

 <li>Created function prototype and stored in <code>.hpp</code> file.</li>

 <li>Created function implementation and stored in <code>.cpp</code> file (see <a href="https://github.com/ILXL-guides/function-file-organization">reference</a>).</li>

 <li>Call function in the driver</li>

 <li>Compiled and ran the driver (<code>main</code>).</li>

 <li>Manually checked for compilation and logical errors.</li>

 <li>Ensured no errors on the unit test (<code>make test</code>).</li>

 <li>Followed advice from the stylechecker (<code>make stylecheck</code>).</li>

 <li>Followed advice from the formatchecker to improve code readbility (<code>make formatcheck</code>).</li>

</ol>

<h1><a id="user-content-code-evaluation" class="anchor" href="https://github.com/peskin55/CPSC121/tree/master/Labs/Lab_14/prob02#code-evaluation" aria-hidden="true"></a>Code evaluation</h1>

Open the terminal and navigate to the folder that contains this exercise. Assuming you have pulled the code inside of <code>/home/student/labex02-tuffy</code> and you are currently in <code>/home/student</code> you can issue the following commands

<pre><code>cd labex02-tuffy</code></pre>

You also need to navigate into the problem you want to answer. To access the files needed to answer problem 1, for example, you need to issue the following command.

<pre><code>cd prob01</code></pre>

When you want to answer another problem, you need to go back up to the parent folder and navigate into the next problem. Assuming you are currently in <code>prob01</code>, you can issue the following commands to go to the parent folder then go into another problem you want to answer; <code>prob02</code> for example.

<pre><code>cd ..cd prob02</code></pre>

Use the <code>clang++</code> command to compile your code and the <code>./</code> command to run it. The sample code below shows how you would compile code saved in <code>statistics_calculator.cpp</code> and <code>main.cpp</code>, and into the executable file <code>main</code>. Make sure you use the correct filenames required in this problem. Take note that if you make any changes to your code, you will need to compile it first before you see changes when running it.

<pre><code>clang++ -std=c++17 main.cpp statistics_calculator.cpp -o main./main</code></pre>

You can run one, two, or all the commands below to <code>test</code> your code, <code>stylecheck</code> your code’s design, or <code>formatcheck</code> your work. Kindly make sure that you have compiled and executed your code before issuing any of the commands below to avoid errors.

<pre><code>make testmake stylecheckmake formatcheck</code></pre>

A faster way of running all these tests uses the <code>all</code> parameter.

<pre><code>make all</code></pre>
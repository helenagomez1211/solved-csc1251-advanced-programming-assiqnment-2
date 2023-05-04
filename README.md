Download Link: https://assignmentchef.com/product/solved-csc1251-advanced-programming-assiqnment-2
<br>
<h1>Aim</h1>

The objectives of this assignment includes:

<ul>

 <li>Learning about encapsulation, inheritance, polymorphism and function overloading</li>

 <li>Apply the concepts learnt by developing a survey and path planning program</li>

</ul>

<h1>Background</h1>

In a theoretical flat-land universe, everything is in 2 dimensions. People, animals, plants to planets, moons, galaxies and even space itself, is in 2D. In our flat-land space (i.e. ‘flat-space’), there is a powerful organization called 2D-StarFIeet (2DSF), whose goals include seeking out new life and civilization via exploration.

While on a routine mission of exploration, the flagship of 2DSF, the Enterprise-2D is trapped in an expanse of space encircled by a massive ring of violent, electrical plasma storm. Data coming in from the sensor array reveals that the only opening in this storm is located at the far end of the enclosed area, from Enterprise-2D’s current location.

In addition, the sensor data also revealed that this area is populated by strange, 2D geometrical shapes, with sizes ranging from a small moon, asteroid, to large planets, or even a star! This implies that to travel to the ‘exit’ at the far end of the storm, you need to understand more about the properties of these shapes and attempt to chart a course to navigate to the exit!

As a Science Officer aboard Enterprise-2D, you need to develop a program that has the following capabilities:

<ol>

 <li>read in sensor data on the strange 2D shapes (via manual input)</li>

 <li>compute the area (‘mass’) of these shapes</li>

 <li>print shapes report (e.g. list of points: on its perimeter, or totally within shape’s area)</li>

 <li>sort shapes data (sorted by special type and area)</li>

</ol>

The next section provides information about the requirements for developing this program.

I

<h1>Task Requirements</h1>

<ol>

 <li>In terms of relative positioning, you may assume a coordinate system with Enterprise-2D at the origin, trying to navigate in a general ‘upper-right’ direction, to get to the exit in the storm. Please refer to Appendix A, which elaborates on this coordinate system and the unit representation of 2D shapes.</li>

</ol>

IMPORTANT For this assignment, you should not assume that the 2D shapes in Appendix A are positioned exactly as shown in Appendix A, nor that there are not more shapes. There WII, however, only be shapes of the types listed in Appendix B

<ol>

 <li>The sensor data coming in from Enterprise-2D’s sensor array provides crucial information about the 2D shapes such as name, special type and location of all vertices (that outlines the perimeter of the shape). Please refer to Appendix B, which provides a more detailed description of the sensor data.</li>

 <li>To assist you in the <u>initial class design</u> of your program, please refer to Appendix C, which illustrates one possible way of designing your program. It also describes a list of requirements which you need to implement, especially those marked under “compulsory”. The classes highlighted in Appendix C are purely meant to store data about the 2D shapes entered into your program by user.</li>

 <li>You are required to implement a main driver class called ‘Assn2’, whose methods are called to start the program. When started, it should print a menu providing the following functionalities

  <ul>

   <li>read in sensor data on the strange 2D shapes (via manual input)</li>

   <li>compute the area (‘mass’) of these shapes</li>

   <li>print shapes report (e.g. list of points on its perimeter, or totally within shapes area)</li>

   <li>sort shapes data (sorted by special type and area)</li>

  </ul></li>

</ol>

Appendix D provides more information about implementing this class.

<ol>

 <li>Once the program is completed and tested to be working successfully, you are highly encouraged to add on “new features” to the program that you feel are relevant to the problem. Additional marks may be awarded subject to the relevancy and correctness of the new functionalities.</li>

 <li>You are to use only C++ language to develop your program. There is no restriction on the IDE as long as your source files can be compiled by g++ compiler (that comes packaged in Ubuntu linux) and executed in the Ubuntu terminal shell environment.</li>

</ol>

<h1>Deliverables</h1>

The deliverables include the following:

<ol>

 <li>The actual working C++ program (soft copy), <u>with comments on each file </u><u>function or block of code</u> to help the tutor understand its purpose.</li>

 <li>A softcopy vord document that elaborates on:

  <ul>

   <li>(Interpreted) requirements of the program</li>

   <li>Diagram / Illustrations of program design</li>

   <li>Summary of implementation of each module in your program</li>

   <li>Reflections on program development (e.g. assumptions made, difficulties faced, what could have been done better, possible enhancements in future, what have you learnt, etc)</li>

  </ul></li>

 <li>A program demo/software testing during lab session. You must be prepared to perform certain tasks / answer any questions posed by the tutor.</li>

</ol>

<ul>

 <li>IMPT: Please follow closely, to the submission instructions in Appendix E, which contains details about what to submit, file naming conventions, when to submit, where to submit, etc.</li>

 <li>The software demo / testing will be held during lab session where you are supposed to submit your assignment. Some time will be allocated for you to present / demonstrate your program’s capabilities during the session.</li>

</ul>

<h1>Gradinq</h1>

Student’s deliverable will be graded according to the following criteria:

Program fulfills all the basic requirements stipulated by the assignment

Successful demonstration of a working program, clarity of explanation / presentation and satisfactory answers provided during Q &amp; A session.

(iii)      Additional effort (e.g. enhancing the program with <u>relevant</u> features over and above task requirements, impressive, ‘killer’ presentation)

After the submission of deliverables, students WII be required undergo a software testing process (to determine the correctness and fulfillment of software requirements.) Further instructions will be given by the Tutor during the subsequent respective labs. Please pay attention as failure to adhere to instructions WII result in deduction of marks.

Tutor’s note:

In the real working world, satisfactory completion of your tasks is no longer enough. The capability, efficiency and robustness of your system to operate under different testing conditions, and the ability to <u>add value</u> <u>communicate</u> and/or <u>demonstrate</u> your ideas with clarity is just as important as correct functioning of your program. The grading criteria is set to imitate such requirements on a ‘smaller scale’.




A

(Coordinate System w.r.t. Enterprise-2D, and the plasma storm)

Y Axis (m KM)

1 unit = 10 million Km

X Axis (m KM)

1 unit =

10 million Km

Enterprise-2D is trapped in this huge ring of electrical plasma storm. The only opening to exit this storm is located in the far ‘upper-right’ of the coordinate system, for e.g. at Point2D (14, 14) !

<u>B</u>

(Description of Sensor Data)

<h2>Name</h2>

The name of the 2D shape reveals the general type of shape encountered. Currently, the values consist of : “Square”, “Rectangle”, “Cross” and “Circle”.

<h2>Special Tvpe</h2>

Enterprise-2D’s sensor has detected that some shapes encloses a ‘vyarp-space’ with the amazing ability to teleport any objects that touches one of its vertex, to any other vertices of the same shape, instantaneously !

This makes it highly desirable, for Enterprise-2D to travel towards this kind of shape, in the hopes of travelling faster, and saving precious fuel at the same time!

There are only 2 values for ‘special type’ : “WS” (Warp-Space) or “NS” (Normal-Space).

<h3>Vertices</h3>

The vertices is actually a set of (x, y) points, that describes the outline of the 2D shape. The number of points in the set, depends on the name of the shape. The table below summarizes the kind of sensor data your program expects to receive.

<table width="698">

 <tbody>

  <tr>

   <td width="125">Name</td>

   <td width="114">Special Type</td>

   <td width="132">No. of Vertices(i.e. x, y, points)</td>

   <td width="327">Actual Vertex Data .</td>

  </tr>

  <tr>

   <td width="125">“Cross”</td>

   <td width="114">‘MIS” or “NS”</td>

   <td width="132">12</td>

   <td width="327">e.g. (I, 3), (1 , 4),                               etc.</td>

  </tr>

  <tr>

   <td width="125">“Square”</td>

   <td width="114">‘WS” or “NS”</td>

   <td width="132">4</td>

   <td width="327"></td>

  </tr>

  <tr>

   <td width="125">“Rectangle”</td>

   <td width="114">‘WS” or “NS”</td>

   <td width="132">4</td>

   <td width="327"></td>

  </tr>

  <tr>

   <td width="125"></td>

   <td width="114"></td>

   <td width="132"></td>

   <td width="327"></td>

  </tr>

 </tbody>

</table>

Note :

As mentioned in the Background section, the 1 <sup>st </sup>capability of your program should allow manual input of the above data.

It is <u>not necessary</u> to prompt user for “No. of Vertices” because the name of the shape will already inform your program about how much vertex data to expect.

For example, when your program prompt for name of the shape, if user enters “Cross”, it is safe for your program to assume that user is going to key a set of 12 (x, y) points later!

<u>C</u>

(Implementation Requirements)

<table width="349">

 <tbody>

  <tr>

   <td width="349">ShapeTwoD</td>

  </tr>

  <tr>

   <td width="349"># name: string# containsWarpSpace: bool</td>

  </tr>

  <tr>

   <td width="349">+ ShapeTwoD (name: string, containsWarpSpace: bool)+ getName () : string+ getContainsWarpSpace () : bool+ toString () : string+ computeArea () : double+ isPointInShape (x: int, y: int) : bool+ isPointOnShape (x: int, y: int) : bool+ setName (name: string)+ setContainsWarpSpace (containsWarpSpace: bool)</td>

  </tr>

 </tbody>

</table>




<h3>Compulsorv requirements</h3>

#1 The parent class is ‘ShapeTwoD’. Any attributes, constructors and methods specified in the diagram must be implemented, with the exact same name, parameter, type and access!

#2       The sub-classes of ShapeTwoD must be named ‘Cross , ‘Square’, ‘Circle’ and ‘Rectangle’.

#3 The method ‘toString ( ) ‘ in class ShapeTwoD is a virtual function that returns a string containing all the values of the attributes in the shape, excluding the array of vertex data. (However, sub-classes of ShapeTwoD must output the array of vertex data, inclusive of any other attribute’s values it inherited)

#4 The method ‘computeArea ( ) ‘ in class ShapeTwoD is a virtual function. It must be override by the sub-classes and implemented individually.

For example, because each sub-class has different number of vertices and values, subclass Cross’s computeArea ( ) implementation would use a different algorithm / formula from sub-class Square’s computeArea ( ) implementation!

Note The sensor data will only provide the locations (vertices) of each 2D shape encountered. You will be required to do the necessary research to <u>derive the formula</u> to compute the area for each shape, based on the set of vertex data (i,e. a set of [ x, y ] points) provided!

#5 The method ‘isPointInShape ( ) ‘ in class ShapeTwoD is a virtual function. It takes in a [ x, y ] location and returns a boolean value indicating whether the location is <u>within the shape’s area</u>. It must be over-ridden by the sub-classes and implemented individually. (PIs refer to sample output in Appendix D)

#6 The method ‘isPointOnShape ( ) ‘ in class ShapeTwoD is also a virtual function. It takes in a [ x, y ] location and returns a boolean value indicating whether the location is <u>found on any lines ioininq the shapes’ vertices</u>! It must be over-ridden by the subclasses and implemented individually. (PIs refer to sample output in Appendix D).

<h3>Other requirements</h3>

For parent class ‘ShapeTwoD’. You are free to add on any additional methods or attributes deemed necessary for your program to provide its services.

<ol>

 <li>Since user will key in the name of the shape, it is possible for you to declare arrays of fixed sizes in the sub-classes to store the coordinate vertices of the shape!</li>

</ol>

<ul>

 <li>You are free to implement any other additional classes you feel necessary so as to provide the required capabilities for this program.</li>

</ul>

<h1>APPENDIX D</h1>

(Implementation info for : Assn 2 driver class)

This class contains the main () method which declares and instantiates all other classes (i.e. Shape2D, Square,           etc) and sets up all the necessary interactions to perform its task.

<table width="312">

 <tbody>

  <tr>

   <td width="312">SWdent ID      : 1234567SWdent Name : Tan Ah Meng ElvisWelcome to Assn2 program!I)        Inptå sensor data2)                  Compute atea (for all records)3)                  Print shapes repott 4) Sort shape dataPlease enter your choice : I[ Input sensor data JPlease enter name of shape : CrossPlease enter special type ; WSPlease enter x-ordinate of m I : IPlease enter y-ordinate of I : IPlease enter x-ordinate of 12 : IPlease enter y-ordinate of 12 : 2Record successfully stored. Going back to main menu .SåJdent ID      : 1234567SWdent Name : Tan Ah Meng Elvis</td>

  </tr>

 </tbody>

</table>

<table width="329">

 <tbody>

  <tr>

   <td width="329">Student ID    • 1234567Student Nanæ : Tan Ah Meng ElvisWelcome to Assn2 program!1)                   Input sensor data2)                   Compute area (for all records)3)                   Print shapes report4)                   Son shapes dataPlease enter your choice : 2Computation completed! ( 5 records were updated )</td>

  </tr>

 </tbody>

</table>

The figure on the left describes a sample interaction between the main menu and ‘Input sensor data’ sub-menu (I <sup>st </sup>example)

Note :

All shapes data should be stored <u>in a Shape2D arrav</u> in the Assn2 driver class. You may assume that no more than 100 shapes will be entered into your program at any one time!

The figure on the right describes a sample interaction between the main menu and ‘Compute area (for al/ records)’ function.

Note : The example assumes the case where t re only 5 shapes input so far, hence, the message that ‘5 records were updated’ !

In this compute area function, you must exhibit <u>polymorphic behavior</u> and <u>dynamic binding</u> by invoking the correct function for each shape stored in the Shape2D array !




<table width="312">

 <tbody>

  <tr>

   <td width="312">Student ID    : 1234567Student Name : Tan Ah Meng ElvisWelcome to Assn2 program!I)         Input sensor data2)                  Comptåe area (for all records)3)                  Print shapes repott 4)  Sott shape dataPlease enter your choice : I[ Input sensor data JPlease enter name of shape : CirclePlease enter special type : NSPlease enter x-otdinate of center : 5Please enter y-otdinate of center : 7Please enter radius (unis) : 2Record successfully stored. Going back to main menu .Student ID    : 1234567Student Nanæ : Tan Ah Meng Elvis</td>

  </tr>

 </tbody>

</table>

The figure on the left describes a sample interaction between the main menu and ‘Input sensor data’ sub-menu (2<sup>nd </sup>example)

Note : For circle, there is no need to enter vertices, as there are no “corners” as opposed to other multi-sided polygon shape. Instead, just prompt user to enter the [x, y] of its center and its radius, as shown on the left

I l

<table width="599">

 <tbody>

  <tr>

   <td width="231">on the right describes a interaction between the main ‘Print shapes repott function.The example assumes the case there has only been 5 sensor input so far.perimeter’ refers to only those on the line drawn between 2 for each pair of vertices the shape’s outline.</td>

   <td rowspan="3" width="369">Student ID       : 1234567Student Name : Tan Ah Meng ElvisWelcome to Assn2 program!1)                   Input sensor data2)                   Compute area (for all records)3)                   Print shapes repott4)                   Sott shapes dataPlease enter your choice : 3Total no. of records available = 5Shape [01Name : SquareSpecial Type : WSArea : 4 units squarePoints on perimeter: (1,2), (2, I), (2, 3), (3, 2)Points within shape : (2, 2)Shape [4]Name : RectangleSpecial Type : NS Area 8 units square Vertices .16), (3, 15), (4, 15), (5, 15), (6, 16), (5, 17), (4, 17), (3, 17)Points within shape : (3, 16), (4, 16), (5, 16)</td>

   <td width="0"></td>

  </tr>

  <tr>

   <td rowspan="2" width="231">2) lies on a line be en 1) and (1, 3) !<u>need to include</u> those points describe the vertices of the shape!within shape’ refers to thoseWiich are totally within the<u>need to include</u>points which de ribe the of the shape!points on the peri eter of shape!</td>

  </tr>

 </tbody>

</table>

The figure sample menu and

Notes : where data records

‘Points on points lying vertices, defining

E.g. (I, vertices (1,

You <u>do not </u>

Wiich

‘Points points shape.

You <u>do not </u>

<ul>

 <li>those vertices</li>

 <li>those the</li>

</ul>

<table width="411">

 <tbody>

  <tr>

   <td width="411">Student ID    : 1234567Student Narne : Tan Ah Meng ElvisWelcome to Assn2 program!I)         Input sensor data2)                  Compute area (for all records)3)                  Print shapes repott4)                  Sott shapes dataPlease enter your choice : 4a)                   Sott by area (ascending)b)                  Sott by area (descending)c)                   Sott by special type and areaPlease select sott option (‘q’ to go main menu) : bSort by area (largest to smallest) .Shape [41Name : RectangleSpecial Type : NSArea : 8 unis squareVertices16), (3, 15), (4, 15), (5, 15), (6, 16), (5, 17), (4, 17), (3, 17)Points within shape : (3, 16), (4, 16), (5, 16)Shape [21Name : SquareSpecial Type : WS Area : 1 unis squareVertices .Point    (6, 6) Point             (6, 7) Point [2] : (7, 7)Point [3] : (7, 6)Points on perimeter : none!Points within shape : none!</td>

  </tr>

 </tbody>

</table>

The figure on the right describes a sample interaction between the main menu and ‘Sort shapes data’ sub-menu.

Note : For ‘sort by special type and area’ option in the sub-menu, shapes with special types ‘WS’ should be displayed first, followed by all shapes with special types ‘NS’.

Within each group of shapes (i.e. WS or NS), display the shapes in descending order!

<h1>APPENDIX E</h1>

Submission Instructions (V. IMP T!!)

<ul>

 <li>Deliverables

  <ol>

   <li>All submissions should be in softcopy, unless otherwise instructed</li>

   <li>For the actual files to be submitted, you typically need to include the followng:

    <ul>

     <li>word document report (e.g. *.doc), save as <u>MS Word 97-2003</u> format the source file(s), (e.g. *.h, *.0, or *.cpp files)</li>

     <li>the executable file, (using Ubuntu g++ compiler), compile into an executable filename with *.exe (e.g. csci251_a2.exe)</li>

    </ul></li>

  </ol></li>

</ul>

<ul>

 <li>How to package</li>

</ul>

Compress all your assignment files into a <u>sinqle zip file</u>. Please use the following naming format

&lt;FT/PT&gt;_&lt;Your Grp&gt;_Assn2_&lt;Stud. No.&gt;_&lt;Name&gt;.zip

Example .

&lt;FTIPT&gt; Use “F T” for Full-Time student, “P T” if you are Part-Time student

&lt;Your Grp&gt; refers to your SIM tutorial group (e.g. TutGrp1 / TutGrp2 / TutGrp / etc.)

Assn2 if you are submitting assignment 2, Assn3 if submitting assignment 3 etc.

&lt;Stud. No.&gt; refers to your LJOW student number (e.g. 1234567)

&lt;Name&gt; refers to your IJOW registered name (e.g. JohnDoeAnderson)

<ul>

 <li>Where to submit</li>

</ul>

Please submit your assignment via Moodle el-earning site.

IMPORTANT NOTE :

<ul>

 <li>To minimize the chances of encountering UNFORSEEN SITUATIONS (mentioned below), please do an <u>EARLY SUBMISSION</u> via Moodle.</li>

 <li>Prior to the relevant assignment deadline, you can upload (and replace) your assignment submissions in Moodle as many times as you like</li>

 <li>It is <u>vour responsibilitv</u> to confirm that you have submitted the final (and correct version) of your deliverables to Moodle <u>before deadline</u></li>

 <li>Any submission uploaded to Moodle after deadline will be considered late</li>

</ul>

In the event of UNFORSEEN SITUATIONS :

( E.g. 3 hrs prior to deadline, there is proof of unforseen events like Moodle site down, unable to upload assignment, undersea internet cable damaged by sea urchins, etc )

Please email your single zip file to your tutor at

<u><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="432030202a717672033a222b2c2c6d202c2e">[email protected]</a></u> for FULL TIME students <u><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="e58696868cd7d0d4a593848d8a8acb868a88">[email protected]</a></u> for PART TIME students

In your email subject line, type in the following information

&lt;FTIPT&gt; &lt;Your Grp&gt; &lt;assignment inf0&gt; &lt;student number&gt; and Fname&gt;




Example:

Totutorh email above)

<table width="632">

 <tbody>

  <tr>

   <td width="95">SubjectNote 1 :Note 2 :</td>

   <td width="537">           FT TutGrp3 Assn2 1234567 JohnDoeAndersonThe timestamp shown on tutor’s email Inbox will be used to determine if the assignment is late or not.After email submission, your mailbox’s s<u>ent f</u>older would have a copy (record) of your sent email, please <u>do not delete</u> that copy It could be used to prove your timely submission, in case the Tutor did not receive your email!</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>When to submit</li>

</ul>

<ol>

 <li>a) Depending on the time-table, a <u>software demo / testinq / presentation</u> for your assignment will be scheduled during the:

  <ul>

   <li>3<sup>rd </sup>– 5<sup>t1 </sup>lab session for the semester (i.e. lab 3 – 5), for Full Time (F T) students</li>

   <li>2<sup>nd </sup>– 4<sup>th </sup>lab session for the semester (i.e. lab 2 – 4), for Part Time (PT) students</li>

  </ul></li>

</ol>

Please consult your tutor for further details. Some time will be allocated for students to demo / present / explain your system design or run test cases during the session.

<ol>

 <li>Please refer to the following table on the different deliverables, submission events &amp; deadlines</li>

</ol>

<table width="654">

 <tbody>

  <tr>

   <td rowspan="2" width="94">Assignment</td>

   <td colspan="2" width="198">Submission Deadline (check Moodle forEXACT date-time )</td>

   <td rowspan="2" width="162">Software Demo / Testing (Tasks), during …</td>

   <td rowspan="2" width="200">Email Demo I Software Testing result files by :</td>

  </tr>

  <tr>

   <td width="102"></td>

   <td width="96"></td>

  </tr>

  <tr>

   <td width="94">1</td>

   <td width="102">Lab 2</td>

   <td width="96">Lab 3</td>

   <td width="162">Lab 2(PT), Lab 3(FT)</td>

   <td width="200">End of Lab 2(PT), Lab 3(FT)</td>

  </tr>

  <tr>

   <td width="94">2</td>

   <td width="102">Lab 3</td>

   <td width="96"></td>

   <td width="162">Lab 3(PT), Lab 4(FT)</td>

   <td width="200">End of Lab 3(PT), Lab 4(FT)</td>

  </tr>

  <tr>

   <td width="94">3</td>

   <td width="102"></td>

   <td width="96">Lab 5</td>

   <td width="162">Lab 4(PT), Lab 5(FT)</td>

   <td width="200">End of Lab 4(PT), Lab 5(FT)</td>

  </tr>

 </tbody>

</table>

<ol>

 <li>IMPORTANT NOTE : Non-submission of any of the above mentioned deliverables will result in ZERO marks! Please check with your Tutor personally if you are unsure!</li>

</ol>

<ul>

 <li>Please help by paying attention to the following …</li>

</ul>

! VERY IMPORTANT !

PLEASE FOLLOW ALL THE GUIDELINES / REQUIREMENTS IN ALL ASSIGNMENT APPENDICES

PLEASE FOLLOW ALL THE SUBMISSION INSTRUCTIONS FROM 1 TO 4 Il

IF YOU ARE NOT SURE,

PLEASE CHECK WITH YOUR TUTOR DURING LABS / LECTURES !

OR

PLEASE EMAIL YOUR ENQUIRIES TO YOUR TUTOR !

MARKS <u>WILL BE DEDUCTED</u> IF YOU FAIL TO FOLLOW INSTRUCTIONS

Examples of marks deduction

<ul>

 <li>Your deliverables / zip file does not follow naming convention</li>

 <li>You have no email subject/ or do not following naming convention</li>

 <li>Your email address / content does not include your name/identity (i.e. tutor cannot easily identify sender)</li>

 <li>Wrong naming or misleading information given</li>

</ul>

(e.g. putting “Assn2” in email subject, when you are submitting “Assnl “)

(e.g. naming “Assnl ” in your zip file, but inside contains Assn2 files )

<ul>

 <li>You email to the WRONG tutor</li>

 <li>Your submission cannot be downloaded and unzipped</li>

 <li>Your program cannot be re-compiled and/or executable file cannot run</li>

 <li>Your report / testing files cannot be opened by Microsoft Word / Excel 2003</li>

 <li>You did not submit / incomplete submission of software demo / testing files etc</li>

</ul>

6) Re-submission administration

After the deadline, (on case-by-case basis), some students / grp may be granted an opportunity for an un-official resubmission by the tutor. If this is so, please adhere to the following instructions carefully:

&lt;Step 1&gt;    Prepare 2 zip files as follows

Zip up for re-submission, <u>proqram files</u> according to the following format

Resubm it &lt;FT/PT&gt;&gt;_&lt;Your Grp&gt;_Assn2_&lt;Stud. No.&gt; _&lt;Name&gt;.zip

Example : Resubmit FT_TutGrp3_ AssnQ1234567_JohnDoeAnderson. zip

Zip up for re-submission, <u>test case results</u> files according to the following format

Resubm it &lt;FT/PT&gt;_&lt;Your Grp&gt;_Assn2_TCResults_&lt;Stud. No.&gt; _&lt;Name&gt;.zip

Example : Resubmit_FT_TutGrp3_Assn2_TCResults_1234567_JohnDoeAnderson. zip

<ul>

 <li>&lt;FTIPT&gt; Use “FT” for Full-Time student, “PT” if you are Part-Time student</li>

 <li>&lt;Your Grp&gt; refers to your SIM tutorial group (e.g. TutGrp1 / TutGrp2 / TutGrp / etc.)</li>

 <li>Assn2 if you are submitting assignment 2, Assn3 if submitting assignment 3 etc.</li>

 <li>&lt;Stud. No.&gt; refers to your I-JOW student number (e.g. 1234567)</li>

</ul>

&lt;Name&gt; refers to your I-JOW registered name (e.g. JohnDoeAnderson)

<ol>

 <li>IMPT To prevent Tutor’s Inbox from blowing up in his face, each student is <u>only allowed to re-submit ONCE</u>, for each assignment only!</li>

</ol>

&lt;Step 2&gt;

Please email your 2 zip files to your tutor’s email (refer to section 3) – Where to submit)

In your email subject line, type in the following information

Resubm it &lt;FTIPT&gt; &lt;Your Grp&gt; &lt;assignment inf0&gt; &lt;student number&gt; and &lt;name&gt;

Example:

To                            tutor’s &amp;Qail befer to s&amp;tion 3) – UKere to sugrnit)

Subject              Resubmit FT TutGrp3 Assn2 1234567 JohnDoeAnderson

IMPORTANT NOTE

Non-submission of any of the above mentioned files, or failure to adhere to submission instructions will result in ZERO marks!

Please check with your Tutor personally if you are unsure!
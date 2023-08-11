# SRMS- Student Result Management System
 VISVESVARAYA TECHNOLOGICAL UNIVERSITY
“JNANA SANGAMA” BELAGAVI- 590 018
 
 A MINI PROJECT REPORT ON 
 “STUDENT RESULT MANAGEMENT SYSTEM”
Submitted in the partial fulfilment of the requirement of the Fifth Semester 
Bachelor of Engineering In 
Computer Science and Engineering 
 Submitted By: 
 Kallesh D R (1BO20CS046) 
 Under The Guidance of 
 SHIVANI KAMBOJ 
 Asst.Professor, Dept of CSE 
 Brindavan College Of Engineering 
DWARAKANAGAR, BAGALUR MAIN ROAD, YELAHANKA, BANGALORE-63 
2022-23 
 DWARAKANAGAR, BAGALUR MAIN ROAD, YELAHANKA, BANGALORE-63 
 DEPARTMENT OF COMPUTER SCIENCE AND ENGINEERING 
 CERTIFICATE 
This is to certify that the Mini Project work entitled “STUDENT RESULT MANAGEMENT 
SYSTEM” is a bonafied work carried out by Kallesh D R in partial fulfillment for the requirements 
of 5th Semester, Bachelor of Engineering in Computer Science and Engineering of Visvesvaraya 
Technological University, Belagavi during the year 2022-23. It is certified that all corrections and 
suggestions indicated for the internal assessment have been incorporated in the report. This mini project 
report has been approved as it satisfies the academic requirements in respect to the work prescribed for 
the Bachelor of Engineering degree. 
______________________________ _________________________________
 Signature of the Guide Signature of the HOD 
 Mrs. SHIVANI KAMBOJ Mr. AVINASH N 
 
 EXAMINERS: 
Name of the Examiner: Signature with Date: 
1.__________________________ ________________________ 
2.__________________________ _________________________ 
 ACKNOWLEDGEMENT
The satisfaction and euphoria that accompanies the successful completion of any task would be
incomplete without mentioning the people who made it possible. Withdeep gratitude, I acknowledge all
those guidance and encouragement, which servedas bacon of light and crowned our efforts with success.
I thank each one of them fortheir valuable support.
I expressmy sincere thanksto Dr.BhagappaPrincipal,BrindavanCollegeofEngineering,Bangalore,for
providing necessary facilities and motivation to carryout mini project work successfully.
I express heartfelt gratitude and humble thanks to Mr.Avinash N HOD,
Dept of CSE, Brindavan College of Engineering, for the constant encouragement and help to carry
out mini project work successfully.
I would also like to express thanks to Project guide Mrs. SHIVANI KAMBOJ, Asst.Prof, Dept of 
CSE, for guiding me to complete mini project work successfully. I would like to mention special thanks
to all the faculty member of Computer Science and Engineering Department, Brindavan College of 
Engineering, Bangalore, for their invaluable support and guidance.
Kallesh D R (1BO20CS046)
 ABSTRACT:
The Student Result Management System is a web-based program that was created to keep track 
of students' grades. The server side language in this program is PHP, the back-end design is MySQL 
and PHP, and the frontend tools are HTML, CSS, and JavaScript. Since SRMS is a computerized 
examination results management system for tertiary students' examination records, the project intends 
to automate semester result management. It will simplify and speed up the result preparation, 
management process, and tasks as a tool for eliminating manual work, dispensing us with maximum 
optimization that prevents both students and administrators from accessing the results. The goal of the 
project is to communicate the exam results to the student in a straightforward manner. It is practical for 
students and institutions to obtain outcomes in a straightforward manner. 
As a result, analyst, you may let students look at the outcomes by providing subject status and 
grades. Students can utilize the system with privileges to read and execute their results by providing 
user names and passwords for a secure login. The registration system is ready for use in the case of a 
new student, and the guest user has simply the ability to read.
CONTENTS
SI.NO CONTENT NAME PAGE NO
 1 Acknowledgment i
 2 Abstract ii
 3 Content iii
CHAPTERS CHAPTER NAME PAGE NO
Chapter 1 Introduction 1
Chapter 2 Analysis 3
Chapter 3 Requirements 4
Chapter 4 System Design 5
Chapter 5 Data Flow Diagram 10
Chapter 6 Entity Relationship Diagram 12
Chapter 7 Schema Diagram 14
Chapter 8 Database Design 16
Chapter 9 Front End Design 20
Chapter 10 Testing 31
Chapter 11 Implementation 32
Chapter 12 Conclusion 43
Chapter 13 Bibliography 44
Chapter1:
 INTRODUCTION
1.1 Introduction:
The major goal of this study is to use a computerized system to improve and 
automate the management and declaration of students' outcomes. The goal of this 
document is to specify the overall software requirements for the Student Result 
Management System, and the efforts have identified the criteria to be deeply and 
correctly defined. The capabilities of the software application System Result 
Management System are described in this specification document. It specifies the 
different limitations that the system must adhere to. This chart provides detailed 
information about a student's current and past semester grades. It contains the 
student's entire academic information, including their registration number, grades, 
total, and average. It may be accessed by professors who will be able to utilize the site 
to analyze results.
1.2 Purpose
The system displays the list of all issues that are open, closed, in progress. If the user can 
get registered by clicking on the logon button and provide the required information as 
specified. Each time the registered customer come on to the site he can makes use of the 
user name and the password that is allocated to him.
1.3 Literature Survey:
HTML stands for Hypertext Markup Language, and it is the standard markup language 
for texts that are meant to be viewed on a web browser. Technologies such as Cascading 
Style Sheets and programming languages like JavaScript can help. 
Cascading Style Sheets (CSS) is a style sheet language for specifying the appearance of 
a document written in a markup language like HTML. Along with HTML and JavaScript, 
CSS is an important part of the World Wide Web.
PHP is a general-purpose programming language that is particularly well suited for web 
development. It was first designed by Rasmus Lerdorf, a Danish-Canadian programmer, 
in 1994. The PHP Group currently produces the PHP reference implementation. 
MySQL is a relational database management system that is free and open-source. "My" 
is the name of co-founder Michael Widenius's daughter, and "SQL" is the acronym for 
Structured Query Language. 
XAMPP is a stands for Cross-Platform, Apache, MySQL, PHP, and Perl, with the Ps 
standing for PHP and Perl, respectively. It's an open-source web-solutions package that 
contains Apache distribution for a variety of servers and command-line executables, as 
well as Apache server, MariaDB, PHP, and Perl modules.
Chapter 2:
ANALYSIS
2.1 Project management
Project management skills are put to good use for this project. Having gone through project
management modules in Time Series Analysis, Optimization and with two interns Project
Management for Business and IT respectively, they enhanced my knowledge on managing a
project. Project management focuses on achieving the objectives by applying five processes
presented in Figure below.
Figure 3.1: Project Development Phases
Figure 2.1: Project Development Phases
Chapter 3: 
 REQUIREMENTS 
 3.1 Software requirements 
Tools used : XAMPP 
Programming languages : PHP 
Front end design :HTML, CSS, JavaScript 
Database : MYSQL 
3.2 Hardware Requirements 
Processor : Intel dual Core, i3 
Ram : 4 GB 
Hard disk : 500 GB 
Chapter 4:
SYSTEM DESIGN
4.1 System Development life cycle
Systems Development Life Cycle (SDLC) is the most common process adopted to develop a
project and notsurprisingly, this project is following this model too. To be precise, waterfall model
is being applied. Waterfall model is a sequential model process where the input of a phase actually
results from the previous phase.
Figure 4.1: SDLC Phases
There are five phases in this model and the first phase is the planning stage. The planning stage
determines the objectives of the project and whether the project should be given the green light to
proceed. This is where the proposal submission comes into picture. After obtaining the approval,
the next phase is analysis. Gathering and analyzing the system and user requirements is essential
for entry to the design step.
With the user requirements gathering completed, there is a need to prepare the resources for the
project. Be it software or hardware components, careful consideration and selection is to be taken
care at this stage. The decision on the appropriate resources to be used is further elaborated under
the subsections below. The next step is to design the system and database structure.
Results from the analysis and preparation that were concluded from the previous stage are put into
action. With the user requirements in mind, the flow of the system is planned and the user interface
is designed to suit their easy navigation needs. In addition, the number of tables, attributes, primary
and unique keys of the database is listed.
After completing the design, actual coding begins. Database is created and codes are written. Some 
of the codes required amendments and improvement to it so these are being developed at this
fourth stage of the waterfall model. With the development completed, testing will begin. Thecodes
and database are tested to ensure the results obtained are as intended. More time is spent onboth 
development and testing stages because it is inevitable to have errors and issues and buffer time
is allocated for troubleshooting.
4.2 Scripting language selection
There are many scripting languages available in the market. VBScript, Perl, JSP (Java Server
Pages), ASP (Active Server Pages) and PHP (Hypertext Pre-processor) are some of those
commonly used. Yet for this project, PHP is the language that is utilized for the coding piece
because it is a server-side, embeddable HTML language. Being a widely-used open-source
scripting language, it is free for everyone to use and is especially suited for web development. On
top of that, the existing system is already using PHP. There are many advantages for using PHP
thus no need for the switch to another scripting language.
Other than being a freeware, there are many free upgrade packages easily available. The other
benefit of choosing PHP is the ease in installation. It can run as a plug in on quite a number of
web servers such as the Apache. On the other hand, JSP requires J2EE server to run and because
it is a Java coded language, it is therefore more complex to understand and to do coding
Further exploring on the processing speed against ASP, PHP is interpreted at run-time and not
compiled into memory whereas ASP is more memory intensive with each ASP language compiler
running in its own processes. This results in slower processing speed for ASP. In addition, ASP
runs more reliably only on Microsoft Windows-based web servers than other web servers.
In conclusion, PHP is the preferred selection due to the ease of usage and it can be uploaded and
run on another platform with minimal change required to be done to the script. Beyond and above,
the compiling time and speed for PHP is faster and more efficient.
4.3 Database selection
There are a variety of databases that we can select from the market. The widely used databasesare
Microsoft Access, Microsoft SQL, Oracle and MySQL. Looking at Microsoft
Access, it does not encourage concurrent usage and it may be inefficient, as the database needs to
be saved into one file. It is also unable to process high speed and large size database as compared
to MySQL.
In terms of costs, Oracle database requires a licensing fee but MySQL database is a freeware. In
addition, MySQL database is easy to install, user friendly, reliable and is able to run on different
platforms. Moreover, PHP can access MySQL database directly without the need to go through
ODBC (Open Database Connectivity).
To conclude, PHP script is able to run faster with MySQL database and the processing time will
definitely be shorter. The pre-school does not require complex and costly software for its database
management system hence MySQL is the ideal database for this project.
4.4 Web server selection
After deciding on the scripting language and database, next is to select the web server that can
support them. Web server is necessary for the delivery of web content to the web browser. As
such, Apache HTTP server which has performance similar with other ’high-performance’ server
is considered Thereafter, research and actual testing have been performed to see the outcome of
the various servers listed in the Figure below. These servers include PHP and MySQL in their
installation packages thus allowing smoother and simpler download process. However, based on
the performance and interface, Wamp or Camp server is the preferred choice.
Figure 4.2: Comparison of web servers
4.5 Front End using HTML,CSS
The Front-End used in this project is HTML along with the CSS language. HTML is the standard
markup language for creating Web pages.
● HTML stands for Hyper Text Markup Language.
● HTML describes the structure of Web pages using markup.
● HTML elements are the building blocks of HTML pages.
● HTML elements are represented by tags.
● HTML tags label pieces of content such as "heading", "paragraph", "table", and so on Browsers
do not display the HTML tags, but use them to render the content of the page.
4.5.1 Advantages of HTML:
1. The first advantage it is widely used.
2. Every browser supports HTML language.
3. Easy to learn and use.
4. It is by default in every window so you don't need to purchase extra software.
5. You can integrate HTML with CSS, JavaScript, php etc.
4.6 The back-end database used in this project is MySQL
It is a language used to interrogate and process data in a relational database. Originally developed
by IBM for its mainframes, SQL commands can be used to interactively work with a database or
can be embedded within a script or programming language as an interface to a database.
Programming extensions to SQL have turned it into a full-blown database programming language,
and all major database management systems (DBMSs) support it.
ANSI standardized SQ. But most DBMSs have some proprietary enhancement, which if used,
makes SQL non- standard. Moving an application from one SQL database to another sometimes
requires tweaking, the age-old problem in this business!
 4.6.1 Advantages of MySQL:
• SQL Queries can be used to retrieve large amounts of records from a database quickly.
• SQL is used to view the data without storing the data into the object
• SQL joins two or more tables and show it as one object to user
• SQL databases use long-established standard, which is being adopted by ANSI &amp; ISO.
Non-SQL databases do not adhere to any clear standard.
• Using standard SQL, it is easier to manage database systems without having to write substantial
amount of code.
Chapter 5:
DATA FLOW DIAGRAM
A data flow is a graphical technique that describes information flow and transforms that are
applied as data move from input to output. The DFD is also known as dataflow graphs or bubble
chart. The DFD is used to represent increasing information flow details. Also, DFD can be stated
as the starting point of the design phase that functionality decomposes
5.1 COMPONENTS OF DATA FLOW DIAGRAM
There are four symbols that are used in the drawing of Data Flow Diagrams
● Entities
External entities represent the sources of data that enter the system or therecipients of data that
leave the system.
● Process
Processes represent data in which data is manipulated by being stored or retrieve ortransformed in
some way. A circle represents it. The process will show the data information or charge.
● Database
Database represents storage of data within the system.
● Data Flow
ER-Diagram
In software engineering, an entity relationship model is an abstract and conceptualrepresentation
of data. Entity relationship modeling is a database modeling method, used to produce a type of
conceptual schema or semantic data model of asystem, often a relational database, and its
requirements a top-down fashion.
Chapter 6:
 ER-Diagram
An Entity–relationship model (ER model) describes the structure of a database with the help of
a diagram, which is known as Entity Relationship Diagram (ER Diagram). An ER model is a design
or blueprint of a database that can later be implemented as a database. The maincomponents
of E-R model are: entity set and relationship set.
What is an Entity Relationship Diagram (ER Diagram)?
An ER diagram shows the relationship among entity sets. An entity set is a group ofsimilar entities
and these entities can have attributes. In terms of DBMS, an entity is a table or attribute of a table
in database, so by showing relationship among tables and their attributes, ER diagram shows the
complete logical structure of a database.
The geometric shapes and their meaning in an E-R Diagram. We will discuss these terms in detail
in the next section (Components of a ER Diagram) of this guide so don’t worry too much about
these terms now, just go through them once.
Rectangle: Represents Entity sets.
Ellipses: Attributes
Diamonds: Relationship Set
Lines: They link attributes to Entity Sets and Entity sets to Relationship Set
Double Ellipses: Multivalued Attributes Dashed Ellipses: Derived Attributes Double
Rectangles: Weak Entity Sets
Double Lines: Total participation of an entity in a relationship se
The ER or (Entity Relational Model) is a high-level conceptual data model diagram. EntityRelation model is based on the notion of real-world entities and the relationship between them.
ER modelling helps you to analyse data requirements systematically to produce a well-designed
database. So, it is considered a best practice to complete ER modelling before implementing your
database.
:E-R Diagram Of Student Result Management System:
Chapter 7:
SCHEMA DIAGRAM
A database schema is the skeleton structure that represents the logical view of the entire database.
It defines how the data is organized and how the relations among them are associated. It formulates
all the constraints that are to be applied on the data. A database schema defines its entities and the
relationship among them. It contains a descriptive detail of the database, which can be depicted
by means of schema diagrams.
An Entity-Relationship Model (ERM) is an abstract and conceptual representation of data. Entityrelationship modeling is a database modeling method, used to produce a type of conceptual
schema or semantic data model of a system, often a relational database, and its requirements in a
top-down fashion.
In order to create an ER schema, you must know three main concepts: entity, attribute and
relationship.
Entity
Relationship model. An entity represents a description of the common features of set of objects of
the real world. Examples of entities are Person, Car, Artist, and Album.
Attribute
An Attribute represents the properties of real-world objects that are relevant for the application
purposes. Attributes are associated with the concept of Entity, with the meaning that all the
instances of the entity are characterized by the same set of attributes. In other words, the entity is
a descriptor of the common properties of a set of objects, and such properties are expressed as
attributes.
Relationship
A Relationship represents semantic connections between entities, like the association between an
artist and his/her album, or between an artist and his/her reviews.
The possible values are one and many. Based on their maximum cardinality constraints,
relationships are called "one-to-one", if both relationships roles have maximum cardinality 1,"oneto-many", if one relationship role has maximum cardinality 1 and the other role has maximum
cardinality N,"many-to-many", if both relationships roles have maximum cardinality N.
:Schema Diagram Referencing The Student Result Management System Database View:
Chapter 8:
Database design
Database is critical for all businesses. A good database does not allow any form of anomalies and
stores only relevant information in an ordered manner. If a database has anomalies, it is affecting
the efficiency and data integrity. For example, delete anomaly arise upon the deletion of a row
which also forces other useful data to be lost. As such, the tables need to be normalized. This
fulfils the last objective of ensuring data are accurate and retrieved correctly. For the database of
this project, the tables are normalized to BCNF as shown below.
Database development
After identifying the tables and columns of the database, the next step is to create them. Basically,
there are two ways to do so. The first option is to create them using commands. Below are some
of the ’create’ and ’insert’ statements. The complete database code is provided
CREATE TABLE `admin` (
 `arminid` int (11) NOT NULL,
 `username` varchar (50) NOT NULL,
 `password` varchar (50) NOT NULL,
 `email` varchar (50) NOT NULL,
 `user type` varchar (30) NOT NULL
) ENGINE=Inorb DEFAULT CHARSET=latin1;
The second option is to use phpMyAdmin. This is a Graphical User Interface (GUI) interface for
building and maintaining the database which is included in the web server, XAMPP package. Thisis a 
simpler way to create the tables if one does not know the usage of commands.
The first step is to create the database as shown in Figure below. The default storage engine in this 
MySQL server is Inorb which has committed, rollback, and crash-recovery capabilities to protect user
data. Following that is to create the tables in the database.
Figure: Table creation in phpMyAdmin
Figure: Database creation in phpMyAdmin
Figure: Attribute creation in phpMyAdmin
After completing the creation, Figure below depicts the contents of the database, providing
information like the number of tables in the database and the number of records in each of them.
The MySQL server, phpMyAdmin, has many other features such as the deletion of tables,
attributes and database. It also provides a mean for exporting or importing data into another
database easily just by selecting the desired option seen at the top of the table in Figure below.
To view the data in one of the tables, this can be done by clicking on the table name listed on the
left menu as per Figure below. The figure illustrates the educator table and there are three records
in it.
Figure 5.5: Data of one table -Admin table
Chapter 9:
FRONT-END AND BACK-END DESIGN
9.1 FRONT-END DESIGN
Front-end web development details
● HTML provides the basic structure of sites, which is enhanced and modified by
othertechnologies like CSS and JavaScript.
● CSS is used to control presentation, formatting, and layout.
● JavaScript is used to control the behaviour of different elements.
HTML
• HTML is at the core of every web page, regardless the complexity of a site or number of
technologies involved. It's an essential skill for any web professional. It's the starting point for
anyone learning how to create content for the web. And, luckily for us, it's surprisingly easy to
learn.
CSS
• CSS stands for Cascading Style Sheets. This programming language dictates how the HTML
elements of a website should actually appear on the frontend of the page.
JavaScript
• JavaScript is a more complicated language than HTML or CSS, and it wasn't released in beta form
until 1995. Nowadays, JavaScript is supported by all modern web browsers and is used on
almost every site on the web for more powerful and complex functionality.
9.2 Connectivity (front end and Back end):
PHP is an amazing and popular language!
It is powerful enough to be at the core of the biggest blogging system on the web 
(Word Press)! It is deep enough to run the largest social network (Facebook)! It is 
also easy enough to be a beginner's first server-side language!
● PHP is an acronym for "PHP: Hypertext Pre-processor".
● PHP is a widely-used, open-source scripting language.
● PHP scripts are executed on the server.
● PHP is free to download and use.
● PHP files can contain text, HTML, CSS, JavaScript, and PHP code.
● PHP code are executed on the server, and the result is returned to the browser as plain
HTML.
● With PHP you are notlimited to output HTML. You can outputimages, PDF files, and
even Flashmovies. You can also output any text, such as XHTML and XML.
LOGIN PAGE:
Dashboard
Create Student Class
Manage Classes
Subject Creation
Manage Subjects
Add Subject Combination
Manage Subjects Combination
Student Admission
Manage Students
Declare Result
Manage Students
Admin Change Password
Front-End In Kannada


Chapter 10:
TESTING
System testing is a series of different test whose primary purpose is to fully 
exercisecomputer- based system.
We can say that it will run according to itsspecifications and in the way users expect.
Special testdata are input for processing, and the results examined. A limited number
of users may be allowedto use the system so that analyst can see whether they try to
use it inunforeseen ways. It is desirable to discover any surprises before the
organization implements the system and depends on it.
▪ We follow Black Box testing.
▪ Black box testing attempts to find errors in following
▪ Incorrect or missing function
▪ Interface errors
▪ Errors in data structure
▪ Initialization and termination errors
Chapter 11:
IMPLEMENTATION
<?php
session_start();
error_reporting(0);
include('includes/config.php');
if($_SESSION['alogin']!=''){
$_SESSION['alogin']='';
}
if(isset($_POST['login']))
{
$uname=$_POST['username'];
$password=md5($_POST['password']);
$sql ="SELECT UserName,Password FROM admin WHERE 
UserName=:uname and Password=:password";
$query= $dbh -> prepare($sql);
$query-> bindParam(':uname', $uname, PDO::PARAM_STR);
$query-> bindParam(':password', $password, PDO::PARAM_STR);
$query-> execute();
$results=$query->fetchAll(PDO::FETCH_OBJ);
if($query->rowCount() > 0)
{
$_SESSION['alogin']=$_POST['username'];
echo "<script type='text/javascript'> document.location = 'dashboard.php'; 
</script>";
} else{
 echo "<script>alert('Invalid Details');</script>";
}
}
?>
<!DOCTYPE html>
<html lang="en">
 <head>
 <meta charset="utf-8">
 <meta http-equiv="X-UA-Compatible" content="IE=edge">
 <meta name="viewport" content="width=device-width, initial-scale=1">
 <title>Admin Login</title>
 <link rel="stylesheet" href="css/bootstrap.min.css" media="screen" >
 <link rel="stylesheet" href="css/font-awesome.min.css" media="screen" >
 <link rel="stylesheet" href="css/animate-css/animate.min.css" 
media="screen" >
 <link rel="stylesheet" href="css/prism/prism.css" media="screen" > <!--
USED FOR DEMO HELP - YOU CAN REMOVE IT -->
 <link rel="stylesheet" href="css/main.css" media="screen" >
 <script src="js/modernizr/modernizr.min.js"></script>
 </head>
 <body class="" style="background-image: 
url(https://c0.wallpaperflare.com/preview/746/11/741/learning-tablet-educationtechnology.jpg); background-position: 536%; height: fit-content; background-size: 
cover;">
 <div class="main-wrapper" style="height: 600%;">
 <div class="">
 <div class="row" style="height: 100%;">
 <!--<div class="col-lg-6 visible-lg-block">--> 
 <section class="section" style="background-color: none; height: 
100%;" width="60%">
 <h1 align="center" style="color: aqua; background-color: gold; 
height: ; width: ; color:green; font-family: cursive;"><marquee behavior="scrol" 
direction="left" scrollamount="10">Student Result Management System By 
Mr.Kallesh D R BGI</marquee> </h1>
 <div class="row mt-40">
 <!-- <div class="col-md-10 col-md-offset-1 pt-50">-->
 <center> <div class="row mt-30 ">
 <div class="col-md-11">
 <div class="panel" style="width: 50%;">
 <div class="panel-heading" style="backgroundcolor: white;">
 <div class="panel-title text-center" 
style="background-color: white; width: 50%;">
 <h4 style="background-color: 
white;">Admin Login</h4>
 </div>
 </div>
 <div class="panel-body p-20" 
style="background-color: white;">
 <div class="section-title">
 <p class="sub-title" style="font-family: 
Arial, Helvetica, sans-serif; font-variant: small-caps; color: white;">Student Result 
Management System</p>
 </div>
 <form class="form-horizontal" method="post" 
style="background-color: white;">
 <div class="form-group">
 <label for="inputEmail3" class="col-sm-2 
control-label">Email</label>
 <div class="col-sm-10">
 <input type="text" name="username" 
class="form-control" id="inputEmail3" placeholder="UserName" required>
 </div>
 </div>
 <div class="form-group">
 <label for="inputPassword3" class="colsm-2 control-label">Password</label>
 <div class="col-sm-10">
 <input type="password" 
name="password" class="form-control" id="inputPassword3" placeholder="Password" 
required>
 </div>
 </div>
 <div class="form-group mt-20">
 <div class="col-sm-offset-2 col-sm-10">
 <button type="submit" name="login" 
class="btn btn-success btn-labeled pull-right">Sign in<span class="btn-label btn-labelright"><i class="fa fa-check"></i></span></button>
 </div>
 </div>
 <div class="col-sm-6">
 <a href="index.html">Back to 
Home</a>
 </div>
 </form> 
 </div>
 </div>
 <!-- /.panel -->
 <p class="text-muted textcenter"><small>Copyright © Kallesh D R | Brought To You By <a 
href="https://kallesh-com.webnode.in">Kallesh D R. </a></small> </p>
 </div>
 <!-- /.col-md-11 -->
 </div>
 <!-- /.row -->
 </div></center>
 <!-- /.col-md-12 -->
 <!-- </div>-->
 <!-- /.row -->
 </section>
 </div>
 <!-- /.col-md-6 -->
 </div>
 <!-- /.row -->
 </div>
 <!-- /. -->
 </div>
 <!-- /.main-wrapper -->
 <!-- ========== COMMON JS FILES ========== -->
 <script src="js/jquery/jquery-2.2.4.min.js"></script>
 <script src="js/jquery-ui/jquery-ui.min.js"></script>
 <script src="js/bootstrap/bootstrap.min.js"></script>
 <script src="js/pace/pace.min.js"></script>
 <script src="js/lobipanel/lobipanel.min.js"></script>
 <script src="js/iscroll/iscroll.js"></script>
 <!-- ========== PAGE JS FILES ========== -->
 <!-- ========== THEME JS ========== -->
 <script src="js/main.js"></script>
 <script>
 $(function(){
 });
 </script>
 <!-- ========== ADD custom.js FILE BELOW WITH YOUR 
CHANGES ========== -->
 </body>
</html>
11.1 Database: `srms`
-- phpMyAdmin SQL Dump
-- version 4.8.3
-- https://www.phpmyadmin.net/
--
-- Host: 127.0.0.1
-- Generation Time: Jun 11, 2020 at 03:54 PM
-- Server version: 10.1.37-MariaDB
-- PHP Version: 7.2.12
SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
SET AUTOCOMMIT = 0;
START TRANSACTION;
SET time_zone = "+00:00";
--
-- Database: `srms`
-- Table structure for table `admin`
--
CREATE TABLE `admin` (
 `id` int(11) NOT NULL,
 `UserName` varchar(100) NOT NULL,
 `Password` varchar(100) NOT NULL,
 `updationDate` timestamp NOT NULL DEFAULT '0000-00-00 00:00:00' ON UPDATE 
CURRENT_TIMESTAMP
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
--
-- Dumping data for table `admin`
--
INSERT INTO `admin` (`id`, `UserName`, `Password`, `updationDate`) VALUES
(1, 'admin', '21232f297a57a5a743894a0e4a801fc3', '2020-06-11 12:26:07');
-- --------------------------------------------------------
--
-- Table structure for table `tblclasses`
--
CREATE TABLE `tblclasses` (
 `id` int(11) NOT NULL,
 `ClassName` varchar(80) DEFAULT NULL,
 `ClassNameNumeric` int(4) NOT NULL,
 `Section` varchar(5) NOT NULL,
 `CreationDate` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
 `UpdationDate` timestamp NOT NULL DEFAULT '0000-00-00 00:00:00' ON UPDATE 
CURRENT_TIMESTAMP
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
-- --------------------------------------------------------
--
-- Table structure for table `tblresult`
--
CREATE TABLE `tblresult` (
 `id` int(11) NOT NULL,
 `StudentId` int(11) DEFAULT NULL,
 `ClassId` int(11) DEFAULT NULL,
 `SubjectId` int(11) DEFAULT NULL,
 `marks` int(11) DEFAULT NULL,
 `PostingDate` timestamp NULL DEFAULT CURRENT_TIMESTAMP,
 `UpdationDate` timestamp NULL DEFAULT NULL ON UPDATE 
CURRENT_TIMESTAMP
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
-- --------------------------------------------------------
--
-- Table structure for table `tblstudents`
--
CREATE TABLE `tblstudents` (
 `StudentId` int(11) NOT NULL,
 `StudentName` varchar(100) NOT NULL,
 `RollId` varchar(100) NOT NULL,
 `StudentEmail` varchar(100) NOT NULL,
 `Gender` varchar(10) NOT NULL,
 `DOB` varchar(100) NOT NULL,
 `ClassId` int(11) NOT NULL,
 `RegDate` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
 `UpdationDate` timestamp NULL DEFAULT NULL ON UPDATE 
CURRENT_TIMESTAMP,
 `Status` int(1) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
-- --------------------------------------------------------
--
-- Table structure for table `tblsubjectcombination`
--
CREATE TABLE `tblsubjectcombination` (
 `id` int(11) NOT NULL,
 `ClassId` int(11) NOT NULL,
 `SubjectId` int(11) NOT NULL,
 `status` int(1) DEFAULT NULL,
 `CreationDate` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
 `Updationdate` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
-- --------------------------------------------------------
--
-- Table structure for table `tblsubjects`
--
CREATE TABLE `tblsubjects` (
 `id` int(11) NOT NULL,
 `SubjectName` varchar(100) NOT NULL,
 `SubjectCode` varchar(100) NOT NULL,
 `Creationdate` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
 `UpdationDate` timestamp NOT NULL DEFAULT '0000-00-00 00:00:00' ON UPDATE 
CURRENT_TIMESTAMP
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
--
-- Indexes for dumped tables
--
--
-- Indexes for table `admin`
--
ALTER TABLE `admin`
 ADD PRIMARY KEY (`id`);
--
-- Indexes for table `tblclasses`
--
ALTER TABLE `tblclasses`
 ADD PRIMARY KEY (`id`);
--
-- Indexes for table `tblresult`
--
ALTER TABLE `tblresult`
 ADD PRIMARY KEY (`id`);
--
-- Indexes for table `tblstudents`
--
ALTER TABLE `tblstudents`
 ADD PRIMARY KEY (`StudentId`);
--
-- Indexes for table `tblsubjectcombination`
--
ALTER TABLE `tblsubjectcombination`
 ADD PRIMARY KEY (`id`);
--
-- Indexes for table `tblsubjects`
--
ALTER TABLE `tblsubjects`
 ADD PRIMARY KEY (`id`);
--
-- AUTO_INCREMENT for dumped tables
--
--
-- AUTO_INCREMENT for table `admin`
--
ALTER TABLE `admin`
 MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=2;
--
-- AUTO_INCREMENT for table `tblclasses`
--
ALTER TABLE `tblclasses`
 MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;
--
-- AUTO_INCREMENT for table `tblresult`
--
ALTER TABLE `tblresult`
 MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;
--
-- AUTO_INCREMENT for table `tblstudents`
--
ALTER TABLE `tblstudents`
 MODIFY `StudentId` int(11) NOT NULL AUTO_INCREMENT;
--
-- AUTO_INCREMENT for table `tblsubjectcombination`
--
ALTER TABLE `tblsubjectcombination`
 MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;
--
-- AUTO_INCREMENT for table `tblsubjects`
--
ALTER TABLE `tblsubjects`
 MODIFY `id` int(11) NOT NULL AUTO_INCREMENT;
COMMIT;
Chapter 12:
CONCLUSION:
 The Student Result Management System (SRMS) is discussed in this work. The product 
is designed to solve the challenges that understudies face in school with their board records. 
The SRMS was built with PHP, MYSQL, HTML, CSS, and JAVASCRIPT, and it was hosted 
locally using Apache web worker. The product improvement concept is also based on the 
Participatory Steady Process Model (PIP Model). A useful breakdown of the framework and 
its core components is provided in order to understand the framework's primary functions. 
Similarly, a use case graph is given to demonstrate the various framework client classes as well 
as the numerous functionality associated with each framework client
Chapter 13:
BIBLIOGRAPHY:
It has been a matter of immense pleasure, honor and challenge to have this
opportunity to take upthis project and complete it successfully. We have obtained
information from various resources todesign and implement our project. We have
acquired most of the knowledge from the Internet.
The following are some of the resources:
● www.w3schools.com
● www.tutorialspoint.com
● Google and YouTube Tutorials
Thank You
The Copy Of The Report Is Now Available In The 
Following Link https://kallesh-d-r.webnode.in/srms-report/
The Source Code Of The Project Is Available in 
https://github.com/KALLESHDR
 
 ©Kallesh D R All Rights Reserved 2022-23

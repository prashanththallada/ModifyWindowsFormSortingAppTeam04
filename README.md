Team - 04
- Sri Ram Teja Komerisetti
- Vyshnavi Srilaxmi Thannir
- Prashanth Kumar Thallada
- Chandra Mouli Kantipudi

-Which algorithm is faster?
-A: Bucket sort

-Where is the entry point of the application? (The place execution begins - provide the fully qualified class name and method name)
-A:static class Program
-    {
-        static void Main()
-        {
-        }
-    }

-What is the name of the code file that displays the main form?
-A: frmMain.cs

-What method does the main form constructor call?  Hint: look at frmMain.cs, right-click if necessary to "View Code", and then find the constructor (the constructor method name is the same as the class name.)
A: InitializeComponent();

-What is the fully qualified name of the class from which the main form is derived? 
A: Form   

-Add code to the Form1_Load method - use intellisense and your IDE to determine: What is this.tbSamples.Value? Set the default value to 10x your team number (if team 1, use 100). If this causes an error, read the error message carefully and make changes as needed.
A: this.tbSamples.Value = 40;

-What is this.cboAlg1?  Set its SelectedIndex to an integer so that the default is Bucket Sort.
A: .cboAlg is one of the two sorted fields for the users to choose.
   this.cboAlg1.SelectedIndex = 3;

-What is this.cboAlg2? Set its SelectedIndex to an integer so that the default is Quick Sort.
A:.cboAlg is to select the sorting algorithm where the user can select it (12 for Quick Sort)
 this.cboAlg2.SelectedIndex = 12;

-Use AppDomain.CurrentDomain.BaseDirectory.ToString() to get the base directory. 
A: using this chunk of code
private string InitializeOutputFolder()
 {
    return AppDomain.CurrentDomain.BaseDirectory.ToString() + "\\output";
 }


-Create a new method called InitializeOutputFolder() and call it - see the suggested content below. What does this method do? 
A: Redirecting(Setting) the current folder to output folder 


-What is this.cmdShuffle?  Call its PerformClick() method before exiting Form1_Load.
A:this.cmdShuffle is the shuffle button on the output panel it is used to shuffle the numbers.


-What is this.cmdSort?  Change its appearance (e.g. ForeColor or BackColor) to highlight it so users will click it. 
A:this.cmdSort is a button on output panel used to start sorting once  you selected the desired algorithm. 


-Make at least one other obvious improvement or customization as desired.
A: Changed the fore color of the Shuffle button to green color.
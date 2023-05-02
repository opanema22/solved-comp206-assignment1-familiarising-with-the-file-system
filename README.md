Download Link: https://assignmentchef.com/product/solved-comp206-assignment1-familiarising-with-the-file-system
<br>
<strong>Ex. 1 —                       Familiarising with the File System </strong>

<ol>

 <li><strong> </strong>Your first task is to create a folder structure similar to the one given below, immediately under your home directory. The structure below represents a typical directory heirarchy that can be employed in developing complex software applications. Below, Projects is a subdirectory of your home directory, COMP206 is a subdirectory of Projects, asgn1 is a subdirectory of COMP206, and so forth. Nothing to be turned in for this question.</li>

</ol>

(Your Home Directory)

<ol start="2">

 <li>Next, starting from you home directory (i.e., pwd shows that you are in your home directory), perform the change directory command, cd, to the asgn1 directory that you just created in the above step (i.e., now the pwd command should show that you are in the asgn1 directory). You <strong>MUST </strong>perform this using a single cd command execution that will take you directly from your home directory to the asgn1</li>

</ol>

1

<ol start="3">

 <li>Now use the ls command to list all the directories that are immediately under the asgn1 The listing should also include the permissions and the owner/group names associated each directory. (Therefore, this should demonstrate that you are the owner of these directories).</li>

</ol>

<strong>Turn in a screen shot of your shell that shows clearly that you executed the </strong>cd <strong>command from the previous question and the </strong>ls <strong>command. The screenshot must be an image, either EX1.PNG or EX1.JPG.</strong>

<strong>Ex. 2 —                      Editing Files with vi </strong>

<ol>

 <li>(a)In the docs directory, create a file by name txt using the vi editor. Enter the following contents in it.</li>

</ol>

Copyright : &lt;your full name&gt;, &lt;year&gt; – All Rights Reserved

Email                   : &lt;your email address&gt;

Dept                    : &lt;name of your department&gt;

<ul>

 <li><strong> </strong>From inside the docs directory, execute the pwd</li>

 <li><strong> </strong>From within the docs directory, execute the ls Make sure that the ls command show that the file was created by your u Next, cat the license file you just created to display its contents.</li>

</ul>

<strong>Turn in a screen shot that shows the </strong>pwd<strong>, </strong>ls<strong>, and </strong>cat <strong>commands and the output that they produce. Include all of it in a single screen shot, EX2 </strong><strong>1.PNG or EX2 1.JPG.</strong>

<ol start="2">

 <li>(a) From within the docs directory, execute the pwd

  <ul>

   <li><strong> </strong>Now make a copy of the license file to the backup directory that you had created before, with a new name, license old.txt, by using the cp command (You MUST execute the cp command from the docs directory).</li>

  </ul></li>

</ol>

<strong>Turn in a screen shot that shows the </strong>pwd<strong>, </strong>cp <strong>commands and the output (if any) that they produce. Include all of it in a single screen shot, EX2 </strong><strong>2.PNG or EX2 2.JPG.</strong>

<strong>Ex. 3 —                    Using grep (4 Points)</strong>

From the docs directory, use pipe to make the ls and grep commands (with appropriate arguments to them) to interact such that it produces the following output. (You would of course have different owner/group names, permissions, file sizes and time stamp for your output. However, the names and order of the files and the content format of the output should be the same.)

-rw——- 1 jdsilv2 root 133 Dec 20 12:21 license.txt drwx—— 2 jdsilv2 root

<strong>Turn in a screen shot that shows the command you executed and the output that it produces as EX3.PNG or EX3.JPG.</strong>
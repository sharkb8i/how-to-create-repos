# How to create git repos
Little guide for create git repos.

### From Scratch (cmd)
<b>1.</b> Create a directory to the project <br/>

   ```sh
   $ mkdir new-project-name
   ```
   
<b>2.</b> Go into the directory <br/>

   ```sh
   $ cd new-project-name
   ```

<b>3.</b> Start the git

   ```sh
   $ git init
   ```
   
<b>4.</b> Create some file and write in

   ```sh
   $ echo some-text-in-the-file > filename.txt
   ```
   
   <i>To see the content of the file...</i><br/>
   ```sh
   $ type filename.txt
   ```
   
   <i>And if you need to edit it...</i><br/>
   ```sh
   $ notepad filename.txt
   ```
   
   <i>Or delete it...</i><br/>
   ```sh
   $ del filename.txt
   ```
   
   <i>Or just to see the files and directories of your project...</i><br/>
   ```sh
   $ dir
   ```
   
<b>5.</b> Add the new created files to your repo

   <i>To add an specific file...</i><br/>
   ```sh
   $ git add filename.txt
   ```
   
   <i>To add all the files...</i><br/>
   ```sh
   $ git add -a
   ```
   
<b>6.</b> Commit the changes

   ```sh
   $ git commit
   ```
   
   <i>Or commit with an message...</i><br/>
   ```sh
   $ git commit -m "commit message"
   ```
<b>7.</b> Finished!



<b>Good Reference:</b><br/>
[Atlassian Bitbucket](https://www.atlassian.com/br/git/tutorials/what-is-version-control)

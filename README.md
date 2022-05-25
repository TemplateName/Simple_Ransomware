<h1>Simple Ransomware</h1>

 ### [Project Inspiration](https://www.youtube.com/watch?v=UtMMjXOlRQc)

<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>
 
- <b>Python</b>

<h2>Environments Used </h2>

- <b>Linux box (Linode server)</b> (Ubuntu 22.04 LTS)

<h2>Program walk-through:</h2>

<p align="center">
Connect to Linux box: <br/>
<img src="https://github.com/TemplateName/PhotoRepo/blob/main/Simple_Ransomware1.png" height="80%" width="80%" alt="Initial Step"/>
<br />
<br />
Create some files:  <br/>
<img src="https://github.com/TemplateName/PhotoRepo/blob/main/Simple_Ransomware2.png" height="80%" width="80%" alt="Creating content within the directory"/>
<br />
<br />
Encoding script: <br/>
<img src="https://github.com/TemplateName/PhotoRepo/blob/main/Simple_Ransomware_Encrypting_code.png" height="80%" width="80%" alt="Malware code"/>
<br />
<br />
Result of the contents of files after running the malware:  <br/>
<img src="https://github.com/TemplateName/PhotoRepo/blob/main/Simple_Ransomware4.png" height="80%" width="80%" alt="Effect of the malware code"/>
<br />
<br />
Decoding script:  <br/>
<img src="https://github.com/TemplateName/PhotoRepo/blob/main/Simple_Ransomware_Decrypting_code.png" height="80%" width="80%" alt="Solution to restoring files back"/>
<br />
<br />
Restore files with failed attempt and successful attempt:  <br/>
<img src="https://github.com/TemplateName/PhotoRepo/blob/main/Simple_Ransomware6.png" height="80%" width="80%" alt="Restored files"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

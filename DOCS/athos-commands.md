## step 1
If you want to build a new app named foo, command: 
<br> `athos foo mkbuild`
1. It will create a folder foo in REPO-AthOS
2. It will create the foo.ini in this folder

Now you can edit foo.ini and make it ready for build - install<p>

---

## step 2
Assume foo.ini is ready, to build and install foo package, command:<br>
`athos foo`<br>


Note: If you have patches for foo, create a **patches** folder next to foo.ini and place them there.<br>
      If foo have depentencies make sure that you have them installed athos will find them if are installed or create an .ini file for every missing dep following **step 1** so athos can find and build them before foo. 



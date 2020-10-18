# TVGuideCombine

# I want to share a setup using "TVGuideCombine.exe" to combine two Tv-Guides "XML" files together into one final-XML file

Note: this .exe file can combine two files only... if you need to combine more than two, please see code in Combine4XML.bat

** First download the content of TVGuideCombine-Download folder

Then create the following directory (with included files) in your local PC:

C:\EPG

TVGuideCombine.exe

Combine2XML.bat

Guide01.xml    # the first Guide to combine

Guide02.xml    # the second Guide to combine



Code:          # for Combine2XML.bat 

   cd\EPG
   
   C:\EPG\TVGuideCombine.exe c:\EPG\FinalTVguide.xml c:\EPG\Guide01.xml c:\EPG\Guide02.xml
   
   
  When you run Combine2XML.bat, here's what will happen:  
 
a FinalTVguide.xml file will be created in the EPG directory

the Guide01.xml & Guide02.xml are combined into 1 FinalTVguide.xml in the EPG directory

TVGuideCombine is a simple C# program "Kerry Mitchell' wrote to pull the channel and programme data from 2 files and combine them.



# In case you want to combine more than two files (4 files) use Combine4XML.bat


Code:          # for Combine4XML.bat 

   cd\EPG
   
   C:\EPG\TVGuideCombine.exe c:\EPG\guide1-2.xml c:\EPG\Guide01.xml c:\EPG\Guide02.xml
   
   C:\EPG\TVGuideCombine.exe c:\EPG\guide3-4.xml c:\EPG\Guide03.xml c:\EPG\Guide04.xml
   
   C:\EPG\TVGuideCombine.exe c:\EPG\FinalTVguide.xml c:\EPG\guide1-2.xml c:\EPG\guide3-4.xml
   
   
   When you run Combine4XML.bat, here's what will happen:  

a guide1-2.xml file will be created in the EPG directory

the Guide01.xml & Guide02.xml are combined into 1 guide1-2.xml in the EPG directory 

a guide3-4.xml file will be created in the EPG directory

the Guide03.xml & Guide04.xml are combined into 1 guide3-4.xml in the EPG directory 

a FinalTVguide.xml file will be created in the EPG directory

the guide1-2.xml & guide3-4.xml are combined into 1 FinalTVguide.xml in the EPG directory


this is the workaround to combine 4 files.
 


**  when needed feel free to change the directory name and the Guide.xml file.

           
		   I wish you finally find easy way to combine xml files easly and fast.


 
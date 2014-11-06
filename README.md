gitHello
========

from eclipse

##First Step  
mark sure your eclipse has the plug-in named egit,then create a new project  
and right click your project->Team->Share project->git->next,click the button  
"Create Repository" and there will be a `.git` in your project directory.  

##Second Step  
choose what you don't want to upload to git `Team->Ignore`.  

##Third Step  
`Team->commit` choose the files you want to commit.Then you have already  
commit your project to local.  

##Fourth Step  
cd your project directory and input  
```
 git remote add origin [url]
```  
'url' is linked to your github repository.  
next execute  
```
 git push -f
```  
Finally,you push your project to github.  

##Fifth Step  
if you want to synchronize your project,you can do `Team-> Fetch`.
Next execute `Team->Merge`.



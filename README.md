## Custom Starter Child Theme

### Instructions:



Edit style.css - especially the "template" field (match parent theme name)



Also remember: grunt build to build the assets folder.

Once everything is working, create a git repository of the same name. Then, locally:  
(You may first have to sudo rm -r .git to start fresh if you have just copied the whole package over)

Don't forget to copy header from parent theme over, and then add:
<link rel="stylesheet" href="<?=get_stylesheet_directory_uri()?>/assets/css/style.min.css" />


git init  
git add --all  
git commit -m "first commit"  
git remote add origin git@github.com:Potato83/*themename*.git  
git push -u origin master  






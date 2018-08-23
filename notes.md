**Init**
========

    > git submodule add <URL> <Name_Of_Submodule>
	> git commit -am "added submodule <name>"
	> git push origin master

**Make Changes to Submodule**
=============================

* Make changes to submodule as you normally would
* Make commits
* cd to superproject dir

    > git status      
	> git add <Name_Of_Submodule>

**How to Push**
===============

* nave to submodule

    > git push origin master 

* nav to superproject dir

    > git push origin master 


**Clone the New Project**
=========================

* clone the project as usual
* nave to superproject dir

	> git submodule update --init 




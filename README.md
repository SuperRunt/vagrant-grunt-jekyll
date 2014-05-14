vagrant box ready for jekyll and gruntjs set up to deal w jekyll builds
=========================================================================

First run
```
$ jekyll new site-name
```
Move all files outside of vagrant dir into site-name/ and cd into that dir.

Then get the initial jekyll build going with 
```
$ jekyll serve
```
Now you can start your watch task: 
```
$ grunt server
```
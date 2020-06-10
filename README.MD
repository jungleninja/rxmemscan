Requirements
===================
 - [theos](https://github.com/theos/theos)
 - [readline](https://github.com/liumazi/libreadline-arm)


Make & Install
-------------

    $ cd rxmemscan
    $ make do FINALPACKAGE=1


Usage
-------------
	$ rxmemscan <pid>
    
| Command | Short | Args          | Desc                                                        |
|---------|-------|---------------|-------------------------------------------------------------|
| list    | l     | [pageNo]      | List search results.                                        |
| search  | s     | [searchVal]   | First search & Search again with [searchVal].               |
| fuzy    | f     | [compareType] | First fuzzy search & Fuzzy search again with [compareType]. |
| reset   | r     | -             | Reset the search state.                                     |
| retype  | -     | -             | Re-select the search value type.                            |
| exit    | -     | -             | Exit the program.                                           |


Screenshots
-------------
![alt tag](https://raw.githubusercontent.com/rainyx/rxmemscan/master/screenshots/screenshot1.jpg)


----------


![alt tag](https://raw.githubusercontent.com/rainyx/rxmemscan/master/screenshots/screenshot2.jpg)


Search String (add by LiuLiu.mz)
-------------
![alt tag](https://raw.githubusercontent.com/liumazi/rxmemscan/master/screenshots/screenshot3.png)


Mazi's Blog
-------------
https://blog.csdn.net/liumazi/article/details/106417276
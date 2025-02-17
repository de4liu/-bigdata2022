# Windows Commands 101

This short tutorial introduces the basics of command line operations in Windows OS. 

## 1. Open a command window window
To open a command window at a given directory, 

- *Windows*: go to the directory in the file explorer, <kbd>Shift+Right click</kbd>, you’ll see "Open a command window here". 
    + If you have git installed. You may also <kbd>right-click</kbd> and "open a git bash window", which is another flavor of command window.
- *Mac OS*: you can enable the "open terminal here" service and access the service using <kbd>Right Click</kbd> (or <kbd>Control + Click</kbd>), then services (more detail here [http://goo.gl/cmMmz](http://goo.gl/cmMmz)).

## 2. Commonly used Windows commands

Purpose | windows | Mac OS
--|--|--
view content of current directory | `dir` | `ls` <br/> `ls -l`
go to a subdirectory*  | `cd dir_name` | `cd dir_name`
go one level up | `cd ..` | `cd ..`
what is the current directory | `dir` | `pwd`

Note: in many cases, you can type <kbd>tab</kbd> to autocomplete the dir/file name

## 3. Run python script from command window
```shell
python python_file_name.py
```


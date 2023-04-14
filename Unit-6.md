open():
    Built-in function
    syntax:
        file = open(filename, mode)
    Modes:
        r:
            read operations
        w:
            open an existing file for a write operation.
            if the file doesn't exist, creates an empty file to write in it.
            if the file contains any data, it will be overwridden.
        a:
            open an existing file for append operation.
            it won't overrwride the existing data.
        r+:
            to read and write data into the file.
            the previous data will be overwritten.
        w+:
            to write and read data.
            override the existing data.
        a+:
            append and read data.
            won't overwrite the existing data.

close():
    A flie remains open until invoked close().
    It is a good practice to close the flie no longer in use to avoid unpredictable behaviour

file.close()
flie.read()
    This gives rise to ValueError.

Writing a file:
    The write() method writes a specified text to the file.
    Where the text will be inserted depends upon the file mode and stream position.
        "a": 
            The text will be inserted at the current file stream position, default at the end of the file.
        "w": 
            The file will be emptied before the text will be inserted at the current file stream position, default at 0.
    writelines() 
        Used to write a list of strings.
    line.split() 
        Used to split the list of the strings.
    fileno() 
        Used to return the file number.
    flush() 
        Used to flush the write buffer of the file stream.
    isatty() 
        Used to return state of the stream (True if inactive).
    readline(n) 
        Used toreturn one line from the file. n is the number of bytes (n is optional).
    truncate(n) 
        Used to resize the file to n bytes.
    rstrip() 
        Used to remove the white spaces including new line characters from the right side of the string from the file.
    fileObject.seek(offset, whence) 
        Used to change the position of file handle to a given specific position. File handle is like a cursor.
    os.rename(current_filename, new_filename)
        Used to rename the file.
    os.remove(filename)
        Used to delete files by supplying the name of the files to be deleted.
    os.mkdir(filename)
        Used to create a new directory.
    os.listdir()
        Used to list the directories contained by the cwd.
    os.rmdir(path)
        Used to remove the directory. If the parameter is left empty, OSError is raised.
    os.path.isdir(path)
        Used to check if the path is a directory.
    os.path.getsize(path)
        Used to get the size of the directory. in bytes. If the invalid path is passed, OSError is raised.
    os.path.exists(path)
        Used to check if the path is a directory exists.
    os.path.isfile(path)
        Used to check if the path is a file.


Getting Current Work Directory (CWD):
    os.getcwd() 
        Used to get the path of the current working directory
    os.getcwdb() 
        Can also be used but it returns a byte string representing the current working directory.
    Both methods don't require any parameters.

Changing Current Work Directory (CWD):
    Every process in the computer system will have a directory associated with it, known as the current working directory.
    os.chdir() is used to change it.
    Parameters passed in it is path/name of the desired directory to which one desires to shift.
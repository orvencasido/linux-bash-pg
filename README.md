# Linux Bash Commands Cheat Sheet

## File and Directory Operations
| Command   | Description                                 | Example Usage                       |
|-----------|---------------------------------------------|-------------------------------------|
| pwd       | Prints current directory                    | pwd                                 |
| cd        | Change directory                            | cd /path/to/dir                     |
| ls        | List files                                  | ls                                  |
| cp        | Copy files                                  | cp source destination               |
| find      | Find files                                  | find /dir -name "file*"             |
| diff      | Compare files                               | diff file1 file2                    |
| chmod     | Change file permissions                     | chmod 777 filename                  |
| mv        | Move/rename file                            | mv source destination               |
| rm        | Remove file                                 | rm -rf filename                     |
| mkdir     | Create folder ("-p" recursive)               | mkdir -p foldername                 |
| rmdir     | Remove folder                               | rmdir foldername                    |
| chown     | Change file owner                           | chown user:group filename           |
| df        | Show disk size ("-h" human readable)         | df -h                               |
| du        | Show folder size                            | du -h foldername                    |

## File Viewing and Editing
| Command   | Description                                 | Example Usage                       |
|-----------|---------------------------------------------|-------------------------------------|
| cat       | Print file contents                         | cat filename                        |
| vim       | Text editor                                 | vim filename                        |
| wc        | Count words/lines/chars                      | wc -c filename                      |
| head      | Print top lines                             | head -n 5 filename                  |
| tail      | Print bottom lines                          | tail -n 5 filename                  |
| nano      | Simple text editor                          | nano filename                       |
| less      | Scrollable file viewer                      | less filename                       |

## Networking
| Command   | Description                                 | Example Usage                       |
|-----------|---------------------------------------------|-------------------------------------|
| curl      | HTTP request ("-I" headers only)             | curl -I destination                 |
| uname     | Show system info                            | uname                               |
| wget      | Download contents                           | wget destination                    |
| scp       | Upload file to remote                       | scp source user@host:destination    |
| ping      | Test domain reachability                     | ping destination                    |
| netstat   | Show network info ("-tulnp" flags)           | netstat -tulnp                      |
| ifconfig  | Display IP, MAC, interface                   | ifconfig                            |

## Text Processing
| Command   | Description                                 | Example Usage                       |
|-----------|---------------------------------------------|-------------------------------------|
| grep      | Search for word in file                      | grep "word" filename                |
| awk       | Filter/print lines                           | awk '{print $1}' filename           |
| sed       | Replace text in file                         | sed 's/word/replace/g' filename     |
| sort      | Sort lines ("-n" numeric, "-r" reverse)       | sort -n filename                    |
| uniq      | Show unique lines                            | uniq filename                       |

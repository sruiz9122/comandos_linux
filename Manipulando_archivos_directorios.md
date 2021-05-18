/Introduccion_Terminal » ls    
command-line-cheat-sheet_93c5cbb9-8acf-423e-a92e-351a461f15ae.pdf
slides-introduccion-termina-linea-comandos.pdf
/Introduccion_Terminal » ls -lat
total 1748
drwxrwxrwx 1 sergio sergio     512 May 17 08:18 .
-rwxrwxrwx 1 sergio sergio 1664983 May 17 08:14 slides-introduccion-termina-linea-comandos.pdf
-rwxrwxrwx 1 sergio sergio  119471 May 17 08:14 command-line-cheat-sheet_93c5cbb9-8acf-423e-a92e-351a461f15ae.pdf
drwxrwxrwx 1 sergio sergio     512 May 17 08:14 ..
/Introduccion_Terminal » mkdir 
miDirectorio
/Introduccion_Terminal » ls    
command-line-cheat-sheet_93c5cbb9-8acf-423e-a92e-351a461f15ae.pdf
miDirectorio
slides-introduccion-termina-linea-comandos.pdf
/Introduccion_Terminal » cd miDirectorio
/Introduccion_Terminal/miDirectorio » mkdir dir1 dir2 dir 3                                 sergio@DESKTOP-M935TPP 
/Introduccion_Terminal/miDirectorio » cd dir1                                               sergio@DESKTOP-M935TPP 
/Introduccion_Terminal/miDirectorio/dir1 » touch file1 file2 file3                          sergio@DESKTOP-M935TPP 
/Introduccion_Terminal/miDirectorio/dir1 » ls                                               sergio@DESKTOP-M935TPP 
file1  file2  file3
/Introduccion_Terminal/miDirectorio/dir1 » cp file1 file_bk                                 sergio@DESKTOP-M935TPP 
/Introduccion_Terminal/miDirectorio/dir1 » ls                                               sergio@DESKTOP-M935TPP 
file1  file2  file3  file_bk
/Introduccion_Terminal/miDirectorio/dir1 » mv file_bk ..                                    sergio@DESKTOP-M935TPP 
/Introduccion_Terminal/miDirectorio/dir1 » cd ..                                            sergio@DESKTOP-M935TPP 
/Introduccion_Terminal/miDirectorio » ls                                                    sergio@DESKTOP-M935TPP 
dir1  dir2  dir3  file_bk
/Introduccion_Terminal/miDirectorio » mv file_bk fileCopy                                   sergio@DESKTOP-M935TPP 
/Introduccion_Terminal/miDirectorio » ls                                                    sergio@DESKTOP-M935TPP 
dir1  dir2  dir3  fileCopy
/Introduccion_Terminal/miDirectorio » rm fileCopy                                           sergio@DESKTOP-M935TPP 
/Introduccion_Terminal/miDirectorio » ls                                                    sergio@DESKTOP-M935TPP 
dir1  dir2  dir3
/Introduccion_Terminal/miDirectorio » rm -i dir3                                            sergio@DESKTOP-M935TPP 
rm: cannot remove 'dir3': Is a directory
/Introduccion_Terminal/miDirectorio » rm -i dir3                                        1 ↵ sergio@DESKTOP-M935TPP 
rm: cannot remove 'dir3': Is a directory
/Introduccion_Terminal/miDirectorio » rm dir3                                           1 ↵ sergio@DESKTOP-M935TPP 
rm: cannot remove 'dir3': Is a directory
/Introduccion_Terminal/miDirectorio » ls                                                1 ↵ sergio@DESKTOP-M935TPP 
dir1  dir2  dir3
/Introduccion_Terminal/miDirectorio » cd ..                                                 sergio@DESKTOP-M935TPP 
/Introduccion_Terminal » ls    
command-line-cheat-sheet_93c5cbb9-8acf-423e-a92e-351a461f15ae.pdf
miDirectorio
slides-introduccion-termina-linea-comandos.pdf
/Introduccion_Terminal » rm -i 
miDirectorio
rm: cannot remove 'miDirectorio': Is a directory
/Introduccion_Terminal » rm miDirectorio
rm: cannot remove 'miDirectorio': Is a directory
/Introduccion_Terminal » cd miDirectorio
/Introduccion_Terminal/miDirectorio » ls                                                    sergio@DESKTOP-M935TPP 
dir1  dir2  dir3
/Introduccion_Terminal/miDirectorio » cd dir1                                               sergio@DESKTOP-M935TPP 
/Introduccion_Terminal/miDirectorio/dir1 » ls                                               sergio@DESKTOP-M935TPP 
file1  file2  file3
/Introduccion_Terminal/miDirectorio/dir1 » remove -i file3                                  sergio@DESKTOP-M935TPP 
zsh: command not found: remove
/Introduccion_Terminal/miDirectorio/dir1 » rm -i file3                                127 ↵ sergio@DESKTOP-M935TPP 
rm: remove regular empty file 'file3'? y
/Introduccion_Terminal/miDirectorio/dir1 » ls                                               sergio@DESKTOP-M935TPP 
file1  file2
/Introduccion_Terminal/miDirectorio/dir1 » tree                                             sergio@DESKTOP-M935TPP 
zsh: command not found: tree
/Introduccion_Terminal/miDirectorio/dir1 » tree -l2                                   127 ↵ sergio@DESKTOP-M935TPP 
zsh: command not found: tree
/Introduccion_Terminal/miDirectorio/dir1 » mv dir1 dir2                               127 ↵ sergio@DESKTOP-M935TPP 
mv: cannot stat 'dir1': No such file or directory
/Introduccion_Terminal/miDirectorio/dir1 » cd ..                                        1 ↵ sergio@DESKTOP-M935TPP 
/Introduccion_Terminal/miDirectorio » ls                                                    sergio@DESKTOP-M935TPP 
dir1  dir2  dir3
/Introduccion_Terminal/miDirectorio » mv dir1 dir2                                          sergio@DESKTOP-M935TPP 
/Introduccion_Terminal/miDirectorio » cd dir2                                               sergio@DESKTOP-M935TPP 
/Introduccion_Terminal/miDirectorio/dir2 » ls                                               sergio@DESKTOP-M935TPP 
dir1
/Introduccion_Terminal/miDirectorio/dir2 » rm -ri dir1                                      sergio@DESKTOP-M935TPP 
rm: descend into directory 'dir1'? y
rm: remove regular empty file 'dir1/file1'? y
rm: remove regular empty file 'dir1/file2'? y
rm: remove directory 'dir1'? y
/Introduccion_Terminal/miDirectorio/dir2 »   
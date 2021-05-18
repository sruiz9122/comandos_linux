/Introduccion_Terminal » mkdir archivos
/Introduccion_Terminal » cd archivos
/Introduccion_Terminal/archivos » touch file.txt dot.txt dot.txt index.html datos1 datos123
/Introduccion_Terminal/archivos » ls *                                                      sergio@DESKTOP-M935TPP 
datos1  datos123  dot.txt  file.txt  index.html
/Introduccion_Terminal/archivos » ls *.txt                                                  sergio@DESKTOP-M935TPP 
dot.txt  file.txt
/Introduccion_Terminal/archivos » ls                                                        sergio@DESKTOP-M935TPP 
datos1  datos123  dot.txt  file.txt  index.html
/Introduccion_Terminal/archivos » ls datos*                                                 sergio@DESKTOP-M935TPP 
datos1  datos123
/Introduccion_Terminal/archivos » ls datos?                                                 sergio@DESKTOP-M935TPP 
datos1
/Introduccion_Terminal/archivos » ls datos???                                               sergio@DESKTOP-M935TPP 
datos123
/Introduccion_Terminal/archivos » ls *.html                                                 sergio@DESKTOP-M935TPP 
index.html
/Introduccion_Terminal/archivos » touc Archivo_mayud.html                                   sergio@DESKTOP-M935TPP 
zsh: command not found: touc
/Introduccion_Terminal/archivos » touch Archivo_mayus.html                            127 ↵ sergio@DESKTOP-M935TPP 
/Introduccion_Terminal/archivos » ls [[:upper:]]*                                           sergio@DESKTOP-M935TPP 
Archivo_mayus.html
/Introduccion_Terminal/archivos » ls -d [[:upper:]]*                                        sergio@DESKTOP-M935TPP 
Archivo_mayus.html
/Introduccion_Terminal/archivos » ls -d [[:lower:]]*                                        sergio@DESKTOP-M935TPP 
datos1  datos123  dot.txt  file.txt  index.html
/Introduccion_Terminal/archivos » ls [ad]*                                                  sergio@DESKTOP-M935TPP 
datos1  datos123  dot.txt
/Introduccion_Terminal/archivos » ls [ai]*                                                  sergio@DESKTOP-M935TPP 
index.html

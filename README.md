# Allegro

Right Click your project under Solution Exploer on the right. Select Properties.

1 - Em Configuration Properties -> Debugging -> Environment, coloque:
PATH=C:\allegro510\bin;%PATH%

2 - Configuration Properties -> C/C++ -> General -> Additional Include Directories, insira
c:\allegro510\include

3 - Configuration Properties -> Liniker -> General -> Additional Library Directories, insira
c:\allegro510\lib

4 - Configuration Properties -> Linker->Input -> Additional Dependencies, insira um ponto e uma virgula bem no final, sem deixar espaco, e logo sem seguida insira:
allegro-5.0.10-monolith-md-debug.lib

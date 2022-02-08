
## Docker 

DevOps, Software Engineering

### Voraussetzung: 
Basic Git command, git cloning a github repository, pushing, pulling

### 1. what is docker?
a platform for building, running, and shipping applications in a consistent matter (it works on my machine!) 
one or more files missing as part of your deployment
different version of the software
different configuration setting 

we can run it anywhere on any machine with docker. Dont have to install all the dependencies. 

and docker itself will automatically download dependencies inside an isolated environment called a container 
ein weiterer Vorteil zum Docker ist, dass wir den Docker und die dazugehörigen Programme beenden ohne dass unsere Machine mit Programmen gefüllt wird. 

Grundsätzlich, Docker ermöglicht uns consistently build, run and ship applications.

### 2. virtual machines vs. containers
an abstraction of a machine, phyical hardware. 

Hypervisor: virutalbox, VMware, Hyper-v(Windows only)
With a hypervisor we can manage virtual machine. Run application
problems:
slow to start
each wm needs a full os system
resource intensive

### 3. architecture of docker
on a linux we run only a linux kernel, on a windows 10 we can run windows and linux kernel. Weil wir Windwos is now shipped wiht a custom built linux kernel. Nun können wir mittels Linux kernel, die Linux application natively on Windows laufen lassen. MacOS hat eine eigene Kernel und es hat kein support for continuous applicaitons. Docker on mac uses a lightweight linux virtual machine to run linux containers. 

### 4. Installing of Docker
Besuche die Website https://docs.docker.com/get-docker/ und klicke auf dein Betriebssystem MacOS, Windows oder Linux. 
Danach gehe die Anforderungen auf der Seite durch. Wichtig bei MacOS ist, dass man wartet bis das Programm installiert wird und öffnet es danach. 

### 5. Development Workflow
t.b.d.




# conky_with_nvidia_gpu
This is an example of a simple conky file that can operate on the background and display the performance of GPU, CPU and RAM. The code is not entirely mine so I do not take ownership of it. My modifications include the NVIDIA-GPU, proper naming of each component, inclusion of tracking bar for each core of the CPU and alterations in colors and general setup display. 

To use download the prerequisite folders for conky by 

> sudo apt-get install conky-all

and then copy and paste the conky file from this repository to your home folder and add a dot in front of the name such as .conkyrc

To run once just run from the terminal

> .conkyrc

or 

> conky & 

To start conky with the computer start-up follow an online guide that is specific to your version of Linux. 

The file works and was designed for Ubuntu 18.04 , CPU: Ryzen 2070x, GPU: Nvidia RTX 2070, G.skill RAM

![conky_image](https://user-images.githubusercontent.com/50516589/60893115-9a40aa00-a260-11e9-9e1e-f416e32f1675.png)


# Future inclusions

Fan Speed for each Fan

Lua circles for a more dynamic conky
 


# What is it?

Tool developed at Marcelo Vázquez's Hack4u Academy (Aka. S4vitar) during the Introduction to Linux course to search for machines solved on the Hack The Box platform by said professor.
You can find the original website tool from S4vitar in the next link:
[htbmachines.github.io/](https://htbmachines.github.io/)

## Example
![Options](/assets/Options.png)

## Use:

The first thing you should do is clone this repository with the following command:

<code>git clone https://github.com/Greco140/Buscador-de-maquinas-resueltas-por-s4vitar.git</code>


Once done, you can go to the folder with:

<code>cd Buscador-de-maquinas-resueltas-por-s4vitar/</code>


Now, give it permission to execute with:

<code>chmod +x htbmachines.sh</code>


Now start it with the following syntax:

<code>./htbmachines.sh</code>

Once this step is done, a menu like the one you can see in the image above will be displayed.

The first parameter you should use is "-u" and that's because before run the script, you need to install a file called "bundle.js", so now execute this: 

<code>./htbmachines.sh -u</code>

* You should see something like this: 
![Options](/assets/Downloaded.png)

The next thing is to re-execute the script with a menu parameter and the characters to search for, which would result in the following syntax:

<code>./htbmachines.sh -parameter "Characters"</code>

* Example:
![Options](/assets/Find%20by%20name%20-m.png)

Additionally, you can search for a machine by difficulty and by operating system simultaneously using both parameters, looking as follows:

<code>./htbmachines.sh -d "Characters" -o "Characters"</code>

![Options](/assets/Difficulty%20and%20SO.png)

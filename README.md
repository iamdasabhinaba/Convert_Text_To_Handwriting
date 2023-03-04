# Convert_Text_To_Handwriting
#This is my 1st project.I made this using python and python module.It convert any text text or data to handwriting.
# Source code

pip install Pywhatkit
import pywhatkit as pkit
text = " The term metaverse was coined in Neal Stephenson's 1992 science fiction novel Snow Crash, where humans, as programmable avatars, interact with each other and software agents, in a three-dimensional virtual space that uses the metaphor of the real world. "
pkit.text_to_handwriting(text,"Demo.jpg",[0,0,0])
print("END")

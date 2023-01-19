#  Virus

This repo contains programs of computer viruses I write for my learning purposes only.

Usually, what a computer virus does is made by three parts:

* The infection vector: this part is responsible to find a target and propagates to this target
* The trigger: this is the condition that once met execute the payload
* The payload: the malicious function that the virus carries around


## Chisokonezo-1

Chisokonzo is a Nyanja term that means Chaos. This is a simple Python program that infects other .py files.
Since python is an interpreted language, its not the best language to write a virus in. And this virus is easily detactable.

**Functions**
|funtion			| description
|-------------------------------|----------------------------|
|**find_files_to_infect()** |the function will return the list of files that can be infected and for each file returned, the virus will spread the infection.|
|**summon_chaos()**| The payload function with the malicious code|

**Testing the virus**

Put the virus in a directory with just another _.py_ file.

## Chisokonezo-2

This is an improved version of Chisokonzo-1 to hide our virus a bit more.

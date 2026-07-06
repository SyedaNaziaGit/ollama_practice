Ollama with CLI (commandLineInterface):

Ollama 
https://ollama.com/download

To use ollama using command line- cli
ollama --version

ollama pull model-name
example:
ollama pull mistral-medium-3.5

to check list of models installed:
ollama ls
or
ollama list

to run the model:
ollama run model-name
example
ollama run mistral-medium-3.5

to exit from model:
/bye

to show other commands similar like help we have:
/show

inorder to set the models parameters or any commands we can use:
/set
and it gives all commands available for setting for that model to finetune
/set parameter

/set system "You are a helpful assistant"
here the message is set for system instruction and now we can see as
/set system

delete model:
ollama rm model-name

Documentation:
https://docs.ollama.com/

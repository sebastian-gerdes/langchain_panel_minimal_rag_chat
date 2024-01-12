## Example from [Coursera course "Langchain chat with your data"](https://www.deeplearning.ai/short-courses/langchain-chat-with-your-data/)

In section "Chat" of the class, a really nice chat is presented in the corresponding Juypter notebook. It works in the cloud but I fail to replicate it on my local machine.

This repository goes along with a question on the internet.

* In order to reproduce my environment:
```
conda env create --name minimal_chat -f minimal_chat.yml
conda env activate minimal_chat
```


* In order to run the app 
    * either:
```
panel serve minimal_chat.ipynb
```
    * or:
```
jupyter-notebook minimal_chat.ipynb
```

Any help to get it running is greatly appreciated - many thanks in advance!
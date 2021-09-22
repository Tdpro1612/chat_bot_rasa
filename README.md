# chat_bot_rasa

### install rasa in post

after install anaconda ,we use anaconda promt

```
conda create -n chat_bot python=3.8
```
```
conda activate chat_bot
```
```
pip install rasa

mkdir tro_ly_ao

cd tro_ly_ao

rasa init

rasa train
```
It very easy ^_^ .it's you lucky.

It has many problem when you install if you don't enough lucky

### Now fix all problem when we install 
- step 1 : this error by tf is err 
```
conda create -n tro_ly python=3.8

conda activate tro_ly

# i go to disc D to install if you use disc C ,you can ignore step here

D:

mkdir trolyao

cd trolyao
```
![trolyao1](https://user-images.githubusercontent.com/61773507/134264797-28ff1e76-e33e-46d6-96b5-4dc588359b52.jpg)

```
pip install rasa

rasa init
#then enter when this ask you directory to save rasa in D:/trolyao if you don't want to save in this you can change directory 
# when you install done,this ask you train demo and you y(yes)  this can be problem 
```
![trolyao2](https://user-images.githubusercontent.com/61773507/134265190-5928b69c-6718-4806-b769-46d473aa103b.jpg)

```
# this error has many reasons:
# not install  Visual C++ 2019 (new computer can not install this) go to and installin this link https://support.microsoft.com/en-us/topic/the-latest-supported-visual-c-downloads-2647da03-1eea-4433-9aff-95f26a218cc0
# computer not support(this computer is very old version,you should sell it and by new.very few...)
# the final reason is pip not recommended in anaconda,you fix by pip uninstall and conda install.

pip uninstall tensorflow

conda uninstall tensorflow

# after you fix tf error, you demo train rasa with code

rasa train
```
- step 2 : wow it appears a new error this is h5py

![anh2](https://user-images.githubusercontent.com/61773507/134265681-9d69d045-4c61-41fa-a902-f6dd28d7c401.jpg)

```
pip uninstall h5py

pip install h5py
```

- Yes,the next error is numpy 

![trolyao4](https://user-images.githubusercontent.com/61773507/134266099-0f18fba3-6595-451d-9e87-c7faa59065f4.jpg)

```
# fix it by numpy=1.18.5

pip install numpy=1.18.5

# after install numpy ,you demo train

rasa train
```
![trainingok](https://user-images.githubusercontent.com/61773507/134267340-84937703-3fb3-4fac-ad6b-24ea303df9e8.jpg)

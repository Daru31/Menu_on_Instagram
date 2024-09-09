# Menu_Auto_Uploader (USH)

Menu_Auto_Uploader is a <mark>script</mark> that crawls same-day meal information within the school's official website and uploads it to Instagram stories. 
In the past, in my school's student council, a person captured and uploaded photos from websites, but to eliminate the hassle, I wrote these scripts to automate.

## How to use:

1. clone repository.

```shell
git clone https://github.com/Daru31/USH-menu-auto-uploader.git
```

2. Install required modules to run code. 

```shell 
pip install -r requirements.txt 
```

3. Change <mark>current_directory</mark>, <mark>USERNAME</mark>, <mark>PASSWORD</mark> inside to yours. 

4. Run setup.py to make <mark>session.json</mark> (This includes your Instagram accout information.) 

```shell 
python setup.py 
```

5. Run <mark>lunchstory.py</mark> to upload now. 

```shell 
python lunchstory.py 
```

6. If you want to schedule to run every 12:00 AM, Run <mark>repeat.py</mark> instead.  

```shell
python repeat.py 
```

1.Install prerequisite packages if you haven’t. In your OS (Windows, Mac, or Linux) terminal, run the following:
$ pip3 install pymongo
2. Change directory (cd) to your data folder (assuming that Materials such as .csv, .json, .py files are in the same folder).
Run the python script LoadMongoDB.py to load data (this may take a while).
$ cd file/to/Data
$ python3 LoadMongoDB.py
If the VM process is unexpectedly terminated while running the code, it is advisable to close any open applications or processes running on your system, such as MySQL or Firefox.
3. Check if the data is correctly loaded into Mongodb. Start the MongoDB shell:
$ mongo / $mongosh
and run the following commands in the shell.
> use academicworld > show collections

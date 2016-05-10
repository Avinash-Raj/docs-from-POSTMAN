# docs-from-POSTMAN
Python script which generates docs from POSTMAN collection url

## How to run?

1. Create a folder `doc` and place it where you likes (mostly inside the project's root folder). And also place `docs.py` file inside the doc folder.
2. From inside the `doc` folder, run the below command. It automatically create doc files for you :-)

````Python
python docs.py postman_collection_url
````
### Example:

1. Clone this repository.
2. Move to the cloned directory from terminal.
3. Run the below command, it would generate 4 doc files. :-)

````Python
python docs.py https://www.getpostman.com/collections/9b3bf6b5d5ff087bdb1d
````

### Screenshot:

![Generated doc](http://i.stack.imgur.com/fqwu3.png)

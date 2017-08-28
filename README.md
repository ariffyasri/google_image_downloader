Download any number of images from Google image search.

Tested on:

- Python 2.7.13
- Windows 10

Requirements:
- selenium==3.5.0

Setup:
- Put geckodriver.exe into Path environment
- run the script

Command:

`python image_download.py <query> <number of images>`

Where:

`<query>` is the the query to search for.

`<number of images>` min(`<number of images>`, total google results) will be downloaded.

Example:

`python image_download.py flat 100`


All the images are downloaded from Google image search. These should be used for educational purposes only. Copyright is owned by the respective websites.

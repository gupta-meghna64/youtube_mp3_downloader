# youtube_mp3_downloader

### What is it ?

This is a python script which lets the user download the mp3 type audio file of any video of youtube. It also gives the user an option to download the lyrics in a text file if the video is a song. It makes it very easy for the user to download a video/song of his choice as it just asks the user to enter the name of the video.The results get better and more precise if the user specifies the name of the artist as well. 
Features - 
* Download mp3 (Type and quality of the file can be changed)
* Get the video details
* Download the lyrics as well

### Libraries/Websites Used 

This is a python script. The libraries used are - 
* requests
* youtube-dl
* Beautiful Soup

The websites used for Scraping are - 
* https://www.youtube.com/
* http://www.azlyrics.com/

### How to use it ?

Clone this project in any of your directory by running the following code: 
<br>
`git clone https://github.com/gupta-meghna64/youtube_mp3_downloader.git`
<br>
Now, first install requests:
<br>
`pip install requests`
<br>
Install BeautifulSoup
<br>
`pip install beautifulsoup4`
<br>
Finally install youtube-dl
<br>
`pip install youtube_dl`
<br>
Windows users will also have to download ffprobe or avprobe incase this is not working in their systems. 

After this extract the code and navigate to that directory in terminal and run the following command : 
<br>
`python youtubecrawl.py`

This should work normally on Linux but may encounter some unwanted errors on windows due to missing softwares.

### What next ?

I plan on developing a UI for this application on Flask and host it on the internet. The future changes will give the user more flexibility to change the video quality, file type and also selecting the video he wants. The changes will make the app more precise. I am also currently looking for a better website to scrape the lyrics.



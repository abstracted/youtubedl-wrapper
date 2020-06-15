<<<<<<< HEAD
# Simple Bulk Music Download Manager

This is a unix command line script used to download from soundcloud, spotify and youtube. 

It is meant to be pointed at an entire users library or playlist and download all items within. 


## How It Works

It functions by using third party scripts, by default [youtube-dl](https://github.com/ytdl-org/youtube-dl/) and [spotify-downloader](https://github.com/Ritiek/Spotify-Downloader).

What makes this a simple download manager is that all of the download settings, including the list of links to download, are manged in configuration files. 

You can then use a tool like a cron job to run the download a specific intervals to ensure your downloads are up to date.

While it downloads, it stores a record of successful downloads in a separate file under the archives directory. If a successful download is recorded to the archive for an item, it will skipped on subsequent download attempts.


## Requirements

- NodeJS
- NPM
- Python 3
- Youtube-dl


Before running the script you will need to run the following in your terminal at the project root:

```
npm i
```


## Configuration

### Download Settings

Download settings for youtube-dl or other downloads is maintained in `download_settings.yaml`. 

### Download List

The list of items to bulk download is maintained in `download_list.yaml`
=======
## Script to bulk download from Youtube

Youtube-DL settings can be modified in download_settings.yml

Download lists can be modified in download_list.yml

### Setup
```
sudo pip3 install youtube-dl
npm i
./run
```
>>>>>>> e277b106f36bd7e939026005c437ec66efb22593

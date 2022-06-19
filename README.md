# Youtube-dl Terminal Gui
Previously called *ytdl-downloader*, youtube-dl terminal gui (or **ytdl-tgui** for short) is a small terminal based gui program that downloads youtube videos in mp4 or mp3 formats. It uses <a href="https://youtube-dl.org/" target="_blank">youtube-dl</a> and <a href="https://ffmpeg.org/" target="_blank">ffmpeg tools</a>. The .exe version of the program was compiled using <a href="https://pyinstaller.org/en/stable/" target="_blank">PyInstaller</a>.

For more information about any errors you may encounter when using the program, I encourage you go look up the youtube-dl documentation <a href="https://github.com/ytdl-org/youtube-dl/" target="_blank">here</a>, since this program is just superimposed over youtube-dl.


[* Developer note - Help wanted!](#contributions--developer-note) 🖋

<br>

## Why should I use this? 💻
To be honest, you don't really need to. The youtube-dl command tool can pretty much achieve everything this program can, however, this program is not meant to replace youtube-dl.

So, *"why should I use this?"* you may ask. Well, if you know how to use youtube-dl by heart, you don't really need this program, but for those who are not familiar with the youtube-dl command tool, and for those who wake up tired after an 8 hour coding session and want to download something quick, this program is meant for you. 

**Youtube-dl terminal gui** simplifies each step of the download for a more user-friendly experience so you don't screw up badly and end up downloading *"never gonna give you up"* in 144p in who knows where in your machine.

In the future, I plan on adding an option to allow you to input your own youtube-dl commands inside the program; a feature I believe some of you will be glad it exist. Although, you know, if you ever feel limited by the constraints of this program, you can always hope back to using normal youtube-dl in the terminal.
<br>

## How does it work ⚙️
**Youtube-dl terminal gui** is simply a kind of gui wrapper of the youtube-dl command tool. A good way to explain how it works would be like this:

<br>
<div align="center">
<img src="./public/img/yt-dl_downloader_explained.svg" width=250>
</div>

<br>
So basically, any command that works in youtube-dl works on this program too. If you check the .py file, "ytdl-terminal-gui.py", you may find that the program works by simply running youtube-dl commands in the background. As I said, this program is not meant to replace youtube-dl, is simply an extension of it.

<br>

## How to use it 🤷‍♂️
There are two ways to open the program:

1) Via python

```bash
# Opens file using your python version
python3 -m location/of/.py/file
```
<br>

2) Via the .exe

```bash
# Opens the file by executing the .exe in the terminal
open location/of/.exe./file
```

<br>



## Dependencies 📊
You need to have youtube-dl and ffmpeg tools installed. Otherwise, both the .py and .exe versions of the program won't work. Also, **youtube-dl terminal gui** is made with Python 3, so be aware the program its imcompatible with older python versions, like Python 2 for example. 

You can install *youtube-dl* and *ffmpeg* with pip using the following commands:

```bash
pip install youtube_dl
```
```bash
pip install ffmpeg
```
<br>

Don't have pip? You can download it running this command:
<br>
<h3>Linux & MacOs</h3>

```bash
python3 -m ensurepip
```

<h3>Windows</h3>

```bash
py -m ensurepip
```
<br>

You don't have python either? You can download it <a href="https://www.python.org/downloads/" target="_blank">here</a>.

<br>

## Contributions & Developer note
For some reason I don't understand, I cannot get PyInstaller to compile multiple .py files into a single one. So, because of this, I was forced to cram everything into a single .py file. Thus, if you ever look inside the .py file, you are going to find that the code its a complete **mess**. 

I don't know what to do, I'm tired, and for some reason PyInstaller just refuses to work. So, for now, I'm leaving it like that until I find a way how to compile multiple .py into a single .exe.

If by chance you know how to do it, feel free to make a pull request, open a issue, create a discussion, or reach me out, either way I'll be happy for any kind of help regarding this matter. Although, if you want to contribute in other parts of the project, in any way or form, feel free to do so, any kind of help will be gladly recieved 😁.

<br>

## License 🔏

[❯ Read the license here →](LICENSE.md) 📄

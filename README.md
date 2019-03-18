

# HTML, CSS Web Page Creation
## phokchanrithisak
HTML, CSS, SaSS frontend building based on 3 different webpages

Open source project of real time streaming (~30 fps) IP/Network security camera on web browser using NodeJS

![Pagespeed Insight by Google](https://lh3.googleusercontent.com/GQDfTofXGJjRIwXnbjuPmX7CgmKiQ_MyCbFWNqstLY2rNBKX6WDqNWxLVsJFyL3-xfvyBupdS8O222zWt-nbF5eDn8tWrfOWzSDBCvGdR_BSGhfidEnKZr96Uaqs2_orq9hzkF7-0xhsp3mm_QY-7mXzIE74vuxoNRKbsOyoXoDWIueFu1goSm0WzadBTcrLRACcBH2LPOBzo4zSxD-yDK7s0vFX32H5X03fvdCyU3zCW8lCymcmDnCAp8oU0668cjOT06wBgOVQYMLb2EzHvEOTx4TQvzlaAvwX_HYcZ88ZfT0JJAf6C793lBiM5xNtwGAyWcFm5UBJL_q4fO10t-2jc_hexKXblR6dLn6JDwOPKnMllJSOa8BdK7lozAEqGvF6yehyoLjFoOgVQafMopAf99MZ8KyC13R_eJoC7hrFVDd20KhCsRcvz8L7Lg1ASJq2JsMW-8QJlBYd_TNNUdx3bOmMZP5Gne2nTAdJtJEP-1UWXsbCSPNAas1Us8WW39QilMCCclIN5rxaCejYSCRcxuTeKWAjlLQ-JjeADjBA7KXswXHvjxMaTWGVJZ7EPZFPjpywgk8oMv7PgdwP5anmQsEWP0YNj8HE0eV8f5n1zjPJ_yczZb-63YOeOS0U7tC4BBrkTPmxSx1fzAPIKqGzX1UdJnUs=w1306-h667-no)

## Getting Started

These instructions will get you a copy of the project to make it up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them

* [Git](https://git-scm.com/downloads) - free and open source distributed version control system 
* [Node.js](https://nodejs.org/en/) - Node.js >= 10.15.0
* [FFmpeg](https://ffmpeg.zeranoe.com/builds/) - Multimedia framework to decode, encode, transcode, mux, demux, stream, filter and play

### Installing

A step by step series of examples that tell you how to get a development up and running

1. Download Git
* [Git](https://git-scm.com/downloads)
2. Open <strong>command prompt/terminal</strong>, Clone this repository to your local machine
```
git clone https://github.com/xpcrts/Steaming-IP-Camera-Nodejs
```
3. Download and install Node.js on your local machine
* [Node.js](https://nodejs.org/en/) - Node.js >= 10.15.0
4. Download and install pre-build FFMPEG Builds on your local machine (Download Build)
* [FFmpeg](https://ffmpeg.zeranoe.com/builds/) - Multimedia framework to decode, encode, transcode, mux, demux, stream, filter and play<br />
* Copy the FFMPEG Zip folder you have just downloaded, paste it into C: drive for simplicity and unzip it.
* Rename the file to <strong>ffmpeg</strong> for simpicity
* After unzipped the file, navigate ffmpeg/bin <br/>
#### On Microsoft Windows
You need to add ffmpeg to <strong>system variables</strong> (For all users) or <strong>User variables</strong> (For specific user)<br />
For research and test, I recommend to add the ffmpeg path to the <strong>system variables</strong> to do that just navigate to:<br/>
a. Control Panel<br/>
b. System and Security<br/>
c. System <br/>
d. Advanced system settings<br/>
e. Environment Variables...<br/>
f. System variables<br/>
g. Path (Double-click on it)<br/>
h. New<br/>
i. Paste this
```C:\ffmpeg\bin```<br/>
j. OK (3 times)<br /><br/>
5. NPM install node-onvif
```
npm install node-onvif -s
```
6.NPM install node-rtsp-stream<br/>
```
npm i node-rtsp-stream -s
```
7.NPM install http-server<br/>
```
npm install http-server -g
```

## Running the tests

1. In the repository, open <i>app.js</i> file
* Change IP address to your camera IP address
* Username of your network camera
* Password of your network camera<br/>
2. Open one command prompt/terminal, navigate to <strong>Streaming-IP-Camera-Nodejs/src</strong> directory and type:
```
http-server
```
hit enter to run<br /><br/>
3. Open another command prompt/terminal, on the same directory path and type: 
```
node app.js
```
hit enter to run<br /><br/>
Now keep those two terminal up and running<br/><br/>
<strong>Preview Streaming Camera on web browser by go to this URL:<br/></strong>
> [127.0.0.1:8000](http://127.0.0.1:8080/)<br/>

You are ready to go.

## Contributing

Please read [CONTRIBUTING.md](https://github.com/xpcrts/Steaming-IP-Camera-Nodejs/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## To-dos

* Streaming Multiple camera channels at once, using 4x4 grid or more
* Customize width and height of canvas
* Improve streaming resolution quality
* Decrease streaming latency 

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/xpcrts/Steaming-IP-Camera-Nodejs/tags). 

## Authors

* **Phok Chanrithisak** - [xpcrts](https://github.com/xpcrts)

See also the list of [contributors](https://github.com/xpcrts/Steaming-IP-Camera-Nodejs/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/xpcrts/Steaming-IP-Camera-Nodejs/blob/master/LICENSE) file for details

## Acknowledgments

* Credit to: Celalettin Erbulut



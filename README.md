# network-pinger
Network Pinger is a very useful tool to check if the website available. Developed on C#, .Net Framework. Needs to be assempled in Visual Studio, Xamarin or MonoDevelop. Works from Windows command line or can be integrated in any software, web service, mobile app, local network tool, etc.
The code works as follows. You upload a list of sites (the number is unlimited) and then the tool processes them and parces only ICMD requests and retuns the processed responses. The response codes are the following:

- IPStatus.Success - the site is available
- IPStatus.Failed - the site is not available.

The tool is also capable of processing errors. Several methods of Object-oriented programming were used in the development of the tool.

The live example of the code implementation: the free software for video download <a href="http://www.freemake.com/free_video_downloader/">Freemake Video Downloader</a>. 
The program checks if the video streaming site is available before the download process could be started.

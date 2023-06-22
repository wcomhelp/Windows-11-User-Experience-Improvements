# Windows 11 User Experience Improvements
Registry Modifications to improve the Windows 11 User Experience.  

### Registry Modifications and Explanation

For your convenience all the registry modifications included in "Windows 11 User Experience Improvements.reg" and run. An explanation of each modification is below.  

1.  When you start the PC, a screen comes before entering the password that goes away when you press any key. It serves no other purpose other than showing a beautiful picture and some extra info about it. Many people may find this screen an annoying extra step to access your PC.  

    NoLockScreen  

2.  Verbose status messages are messages you see when Windows is starting or shutting down such as the "Preparing your desktop" message. Basically, it tells you exactly what is Windows doing currently which is causing the delay in startup/shutdown. By default, these messages are very limited and won't give all the information. If you are seeing long delays while shutting down or starting up, then you can turn on these verbose status messages to see exactly what is causing the delay and possibly fix the problem.

    Verbosestatus

3.  Windows 11 has a new context menu that is small in size and has most of the options hidden behind the 'Show more options' button that opens the classic context menu. I personally don't like the new context menu as most of the time I have to hit the 'Show more options' button anyway. Why make this a 2-click process when you can just open the old context menu on the first attempt?

    @=""

4.  If you have multiple windows of an app opened (like browser windows), then switching back to it will open a thumbnails row for you to choose which window you want to access. This basically makes switching between two different apps tedious as you have to click twice every time.

    LastActiveClick

5.  Microsoft replaced the classic Photo Viewer app with the new Photos app. However, if you don't like the new Photos app, you can restore the classic Photo Viewer app

    PhotoViewer.FileAssoc.Tiff

6.  Most users utilize Windows 11's search tool to find files and installed software. However, that search utility also provides Bing web results whenever you enter keywords. Those online results can get mixed up with file and app searches. So, many users prefer to remove the Bing search suggestions.

    DisableSearchBoxSuggestions

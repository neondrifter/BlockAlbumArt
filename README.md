Let's say you love music. And you love exploring it. But you don't necessarily like all album art. Maybe you think it's just too noisy and it clutters up your experience of music streaming?

Well, for several years, I've used my own solution and after seeing that literally no one else has written any kind of guide on how to disable album art in Spotify online, I've decided to share my method.

There are two methods you can take, one is simpler than the other.
	
 1. THE HARD(ish) WAY: You can modify the hosts file of your device to block all hosts responsible for album art. This is easier on some devices, more difficult on others. This is easy on Windows for example. This requires root on Android and I believe is near impossible on an Apple product. (ie: I don't know about Apple, I only have an iPad and I used method 2 for it.)
	
 2. THE EASY WAY: You can download a third party app that uses DNS filtering to block the hosts responsible for album art.

In this guide, I'm going to show you how to do this using method 2. If you want to use method 1, do some googling about how to modify the hosts file of your device.

First, the app we're going to use is called AdGuard. There are other DNS Filter apps out there, but I think AdGuard is the most user friendly. It's an excellent app meant for blocking ads and tracking and all sorts of stuff on your device. It's also available on just about anything. iPad, iPhone, Android devices,  Windows, etc...

So let's get started.

Prerequisites:
- Download AdGuard onto whatever device you use Spotify on. https://adguard.com/en/welcome.html
- Download the SpotifyBlock file provided above as a .txt file onto any device you use Spotify on. Remember where you save the file.

STEPS:
1. Open and set up AdGuard on your device. No need to subscribe to premium for our purposes.
2. Tap the Shield Icon at the bottom.
3. Tap DNS Protection.
4. Tap DNS filters.
5. Tap User rules. This is where you enter the hosts that you want blocked.
6. You can click the Add user rule button to add each host manually. The hosts are those individual lines within the SpotifyBlock file above.

OR

7. Tap the 3 dots in the top right corner. Tap import. Find the SpotifyBlock file you downloaded earlier and import that.

If done correctly, all the hosts from the SpotifyBlock file should now be individually listed below the "Add user rule" button with green checks to the left of them.

AdGuard is now enabled to block these hosts and therefore, will block all album art on Spotify!

BUT WAIT! If you've already used your Spotify app before, then it already has some album art stored on it from your past use. This art will continue to show up regardless of our filters unless we do the following...

1. Long press the Spotify icon.
2. Tap the App info button.
3. Tap Storage.
4. Tap to clear Cache.
5. Tap to clear Data.

This will not uninstall Spotify but it will sign you out of the app so open the app back up, sign in and you should now have an album art free Spotify experience! NOTE: If you're on an Apple device, just uninstall Spotify and reinstall it and you should get the same results.

NOTE: I cannot for the life of me figure out how to disable the album art for the "This is..." buttons. You know the ones that are like "This is Elton John" and it's got a picture of the artist? That's the only one I don't know how to filter. Other than that, this disables everything else.

If album art ever slips through, it means that something happened to the connection OR Spotify updated their hosts. The best you can do is clear the app cache and data again and launch it to see if that corrects the issue. If it doesn't, you'll need to find which new host is providing the unwanted material and add that to your DNS User rules as well. 

title: org.gateshipone.odyssey

# org.gateshipone.odyssey

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'org.gateshipone.odyssey.playbackservice.IOdysseyPlaybackService org.gateshipone.odyssey.playbackservice.PlaybackServiceConnection.getPBS()' on a null object reference
// 	at org.gateshipone.odyssey.fragments.AllTracksFragment.playTrack(AllTracksFragment.java:229)
// 	at org.gateshipone.odyssey.fragments.AllTracksFragment.onItemClick(AllTracksFragment.java:152)
// 	at android.widget.AdapterView.performItemClick(AdapterView.java:310)
// 	at android.widget.AbsListView.performItemClick(AbsListView.java:1145)
// 	at android.widget.AbsListView$PerformClick.run(AbsListView.java:3066)
// 	at android.widget.AbsListView$3.run(AbsListView.java:3903)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```




title: net.opendasharchive.openarchive.release

# net.opendasharchive.openarchive.release

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
// 	at android.os.Handler.<init>(Handler.java:200)
// 	at android.os.Handler.<init>(Handler.java:114)
// 	at info.guardianproject.nearby.bluetooth.BluetoothReceiver$2.<init>(BluetoothReceiver.java:206)
// 	at info.guardianproject.nearby.bluetooth.BluetoothReceiver.<init>(BluetoothReceiver.java:205)
// 	at net.opendasharchive.openarchive.nearby.NearbyActivity.startClient(NearbyActivity.java:354)
// 	at net.opendasharchive.openarchive.nearby.NearbyActivity.access$900(NearbyActivity.java:54)
// 	at net.opendasharchive.openarchive.nearby.NearbyActivity$6.run(NearbyActivity.java:262)

```




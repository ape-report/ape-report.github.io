title: de.phoenixstudios.pc_dimmer

# de.phoenixstudios.pc_dimmer

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NumberFormatException: Invalid int: "4326555255"
// 	at java.lang.Integer.invalidInt(Integer.java:138)
// 	at java.lang.Integer.parse(Integer.java:413)
// 	at java.lang.Integer.parseInt(Integer.java:367)
// 	at java.lang.Integer.parseInt(Integer.java:334)
// 	at de.phoenixstudios.pc_dimmer.Main.StageSetupCallbackToMain(Main.java:1639)
// 	at de.phoenixstudios.pc_dimmer.stagesetup.onClick(stagesetup.java:50)
// 	at android.view.View.performClick(View.java:5204)
// 	at android.view.View.onKeyUp(View.java:9885)
// 	at android.widget.TextView.onKeyUp(TextView.java:6245)
// 	at android.view.KeyEvent.dispatch(KeyEvent.java:2664)
// 	at android.view.View.dispatchKeyEvent(View.java:9240)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.support.v4.view.ViewPager.dispatchKeyEvent(ViewPager.java:2567)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at com.android.internal.policy.PhoneWindow$DecorView.superDispatchKeyEvent(PhoneWindow.java:2395)
// 	at com.android.internal.policy.PhoneWindow.superDispatchKeyEvent(PhoneWindow.java:1727)
// 	at android.app.Activity.dispatchKeyEvent(Activity.java:2731)
// 	at com.android.internal.policy.PhoneWindow$DecorView.dispatchKeyEvent(PhoneWindow.java:2310)
// 	at android.view.ViewRootImpl$ViewPostImeInputStage.processKeyEvent(ViewRootImpl.java:4127)
// 	at android.view.ViewRootImpl$ViewPostImeInputStage.onProcess(ViewRootImpl.java:4089)
// 	at android.view.ViewRootImpl$InputStage.deliver(ViewRootImpl.java:3642)
// 	at android.view.ViewRootImpl$InputStage.onDeliverToNext(ViewRootImpl.java:3695)
// 	at android.view.ViewRootImpl$InputStage.forward(ViewRootImpl.java:3661)
// 	at android.view.ViewRootImpl$AsyncInputStage.forward(ViewRootImpl.java:3787)
// 	at android.view.ViewRootImpl$InputStage.apply(ViewRootImpl.java:3669)
// 	at android.view.ViewRootImpl$AsyncInputStage.apply(ViewRootImpl.java:3844)
// 	at android.view.ViewRootImpl$InputStage.deliver(ViewRootImpl.java:3642)
// 	at android.view.ViewRootImpl$InputStage.onDeliverToNext(ViewRootImpl.java:3695)
// 	at android.view.ViewRootImpl$InputStage.forward(ViewRootImpl.java:3661)
// 	at android.view.ViewRootImpl$InputStage.apply(ViewRootImpl.java:3669)
// 	at android.view.ViewRootImpl$InputStage.deliver(ViewRootImpl.java:3642)
// 	at android.view.ViewRootImpl$InputStage.onDeliverToNext(ViewRootImpl.java:3695)
// 	at android.view.ViewRootImpl$InputStage.forward(ViewRootImpl.java:3661)
// 	at android.view.ViewRootImpl$AsyncInputStage.forward(ViewRootImpl.java:3820)
// 	at android.view.ViewRootImpl$ImeInputStage.onFinishedInputEvent(ViewRootImpl.java:3981)
// 	at android.view.inputmethod.InputMethodManager$PendingEvent.run(InputMethodManager.java:2253)
// 	at android.view.inputmethod.InputMethodManager.invokeFinishedInputEventCallback(InputMethodManager.java:1874)
// 	at android.view.inputmethod.InputMethodManager.finishedInputEvent(InputMethodManager.java:1865)
// 	at android.view.inputmethod.InputMethodManager$ImeInputEventSender.onInputEventFinished(InputMethodManager.java:2230)
// 	at android.view.InputEventSender.dispatchInputEventFinished(InputEventSender.java:141)
// 	at android.os.MessageQueue.nativePollOnce(Native Method)
// 	at android.os.MessageQueue.next(MessageQueue.java:323)
// 	at android.os.Looper.loop(Looper.java:135)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



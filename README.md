- 👋 Hi, I’m @looxooxi
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
looxooxi/looxooxi is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
## Exception
* __User Action:__ requested comments
* __Request:__ Start loading: https://www.youtube.com/watch?v=GmSuMTaKZKE
* __Content Country:__ FR
* __Content Language:__ fr-FR
* __App Language:__ fr_FR
* __Service:__ YouTube
* __Version:__ 0.21.7
* __OS:__ Linux Android 10 - 29
<details><summary><b>Crash log </b></summary><p>

```
org.schabi.newpipe.extractor.exceptions.ParsingException: Could not parse json data for comments
	at org.schabi.newpipe.extractor.services.youtube.extractors.YoutubeCommentsExtractor.getPage(YoutubeCommentsExtractor.java:100)
	at org.schabi.newpipe.extractor.services.youtube.extractors.YoutubeCommentsExtractor.getInitialPage(YoutubeCommentsExtractor.java:55)
	at org.schabi.newpipe.extractor.utils.ExtractorHelper.getItemsPageOrLogError(ExtractorHelper.java:19)
	at org.schabi.newpipe.extractor.comments.CommentsInfo.getInfo(CommentsInfo.java:40)
	at org.schabi.newpipe.extractor.comments.CommentsInfo.getInfo(CommentsInfo.java:25)
	at org.schabi.newpipe.util.ExtractorHelper.lambda$getCommentsInfo$7(ExtractorHelper.java:155)
	at org.schabi.newpipe.util.-$$Lambda$ExtractorHelper$60N_-UL7E5eaxFaFO1bZZmnfwM8.call(Unknown Source:4)
	at io.reactivex.rxjava3.internal.operators.single.SingleFromCallable.subscribeActual(SingleFromCallable.java:43)
	at io.reactivex.rxjava3.core.Single.subscribe(Single.java:4813)
	at io.reactivex.rxjava3.internal.operators.single.SingleDoOnSuccess.subscribeActual(SingleDoOnSuccess.java:35)
	at io.reactivex.rxjava3.core.Single.subscribe(Single.java:4813)
	at io.reactivex.rxjava3.internal.operators.single.SingleSubscribeOn$SubscribeOnObserver.run(SingleSubscribeOn.java:89)
	at io.reactivex.rxjava3.core.Scheduler$DisposeTask.run(Scheduler.java:614)
	at io.reactivex.rxjava3.internal.schedulers.ScheduledRunnable.run(ScheduledRunnable.java:65)
	at io.reactivex.rxjava3.internal.schedulers.ScheduledRunnable.call(ScheduledRunnable.java:56)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:301)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1167)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:641)
	at java.lang.Thread.run(Thread.java:929)
Caused by: com.grack.nanojson.JsonParserException: Unexpected character: < on line 1, char 1
	at com.grack.nanojson.JsonTokener.createParseException(Unknown Source:44)
	at com.grack.nanojson.JsonTokener.advanceToToken(Unknown Source:118)
	at com.grack.nanojson.JsonParser.advanceToken(Unknown Source:12)
	at com.grack.nanojson.JsonParser.parse(Unknown Source:1)
	at com.grack.nanojson.JsonParser$JsonParserContext.from(Unknown Source:19)
	at org.schabi.newpipe.extractor.services.youtube.extractors.YoutubeCommentsExtractor.getPage(YoutubeCommentsExtractor.java:98)
	... 19 more

```
</details>
<hr>

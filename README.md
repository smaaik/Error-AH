# Error-AH
Combat logg

[14:14:13] [ForkJoinPool.commonPool-worker-6/WARN]: java.util.concurrent.CompletionException: java.lang.NullPointerException: Cannot invoke "com.backtobedrock.augmentedhardcore.runnables.CombatTag.AbstractCombatTag.restart(com.backtobedrock.augmentedhardcore.domain.Killer)" because "e" is null
[14:14:13] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.CompletableFuture.encodeThrowable(CompletableFuture.java:315)
[14:14:13] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.CompletableFuture.completeThrowable(CompletableFuture.java:320)
[14:14:13] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:722)
[14:14:13] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.CompletableFuture$Completion.exec(CompletableFuture.java:483)
[14:14:13] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.ForkJoinTask.doExec(ForkJoinTask.java:373)
[14:14:13] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.ForkJoinPool$WorkQueue.topLevelExec(ForkJoinPool.java:1182)
[14:14:13] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.ForkJoinPool.scan(ForkJoinPool.java:1655)
[14:14:13] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1622)
[14:14:13] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)
[14:14:13] [ForkJoinPool.commonPool-worker-6/WARN]: Caused by: java.lang.NullPointerException: Cannot invoke "com.backtobedrock.augmentedhardcore.runnables.CombatTag.AbstractCombatTag.restart(com.backtobedrock.augmentedhardcore.domain.Killer)" because "e" is null
[14:14:13] [ForkJoinPool.commonPool-worker-6/WARN]:     at com.backtobedrock.augmentedhardcore.domain.data.PlayerData.lambda$onCombatTag$16(PlayerData.java:464)
[14:14:13] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.ArrayList.forEach(ArrayList.java:1511)
[14:14:13] [ForkJoinPool.commonPool-worker-6/WARN]:     at com.backtobedrock.augmentedhardcore.domain.data.PlayerData.onCombatTag(PlayerData.java:464)
[14:14:13] [ForkJoinPool.commonPool-worker-6/WARN]:     at com.backtobedrock.augmentedhardcore.eventListeners.ListenerPlayerDamageByEntity.lambda$onPlayerDamage$0(ListenerPlayerDamageByEntity.java:35)
[14:14:13] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:718)
[14:14:13] [ForkJoinPool.commonPool-worker-6/WARN]:     ... 6 more
[14:14:14] [ForkJoinPool.commonPool-worker-6/WARN]: java.util.concurrent.CompletionException: java.lang.NullPointerException: Cannot invoke "com.backtobedrock.augmentedhardcore.runnables.CombatTag.AbstractCombatTag.restart(com.backtobedrock.augmentedhardcore.domain.Killer)" because "e" is null
[14:14:14] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.CompletableFuture.encodeThrowable(CompletableFuture.java:315)
[14:14:14] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.CompletableFuture.completeThrowable(CompletableFuture.java:320)
[14:14:14] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:722)
[14:14:14] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.CompletableFuture$Completion.exec(CompletableFuture.java:483)
[14:14:14] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.ForkJoinTask.doExec(ForkJoinTask.java:373)
[14:14:14] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.ForkJoinPool$WorkQueue.topLevelExec(ForkJoinPool.java:1182)
[14:14:14] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.ForkJoinPool.scan(ForkJoinPool.java:1655)
[14:14:14] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1622)
[14:14:14] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165)
[14:14:14] [ForkJoinPool.commonPool-worker-6/WARN]: Caused by: java.lang.NullPointerException: Cannot invoke "com.backtobedrock.augmentedhardcore.runnables.CombatTag.AbstractCombatTag.restart(com.backtobedrock.augmentedhardcore.domain.Killer)" because "e" is null
[14:14:14] [ForkJoinPool.commonPool-worker-6/WARN]:     at com.backtobedrock.augmentedhardcore.domain.data.PlayerData.lambda$onCombatTag$16(PlayerData.java:464)
[14:14:14] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.ArrayList.forEach(ArrayList.java:1511)
[14:14:14] [ForkJoinPool.commonPool-worker-6/WARN]:     at com.backtobedrock.augmentedhardcore.domain.data.PlayerData.onCombatTag(PlayerData.java:464)
[14:14:14] [ForkJoinPool.commonPool-worker-6/WARN]:     at com.backtobedrock.augmentedhardcore.eventListeners.ListenerPlayerDamageByEntity.lambda$onPlayerDamage$0(ListenerPlayerDamageByEntity.java:35)
[14:14:14] [ForkJoinPool.commonPool-worker-6/WARN]:     at java.base/java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:718)
[14:14:14] [ForkJoinPool.commonPool-worker-6/WARN]:     ... 6 more

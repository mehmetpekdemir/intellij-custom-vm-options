# intellij-custom-vm-options


```
-Xms1024m
-Xmx4096m

-XX:NewRatio=1
-XX:ReservedCodeCacheSize=1024m
-XX:+UseG1GC
-XX:SoftRefLRUPolicyMSPerMB=250
-XX:CICompilerCount=2
-XX:+HeapDumpOnOutOfMemoryError
-XX:-OmitStackTraceInFastThrow
-XX:+OptimizeStringConcat
-XX:+UseCodeCacheFlushing
-XX:+UseStringCache

-XX:+AggressiveOpts

-XX:CompileThreshold=10000
-XX:LargePageSizeInBytes=256m
-XX:MaxNewSize=512m
-XX:MaxPermSize=1024m
-XX:ParallelGCThreads=4
-XX:ReservedCodeCacheSize=512m

-Dsun.io.useCanonCaches=false
-Djdk.http.auth.tunneling.disabledSchemes=""
-Djdk.attach.allowAttachSelf=true
-Djdk.module.illegalAccess.silent=true
-Dkotlinx.coroutines.debug=off

-XX:ErrorFile=$USER_HOME/java_error_in_idea_%p.log
-XX:HeapDumpPath=$USER_HOME/java_error_in_idea.hprof
-ea
```

# Cesium
The Minecraft modpack create: corporate.

Jvm args
-XX:+UnlockExperimentalVMOptions
-XX:+UseCompactObjectHeaders
-XX:+TieredCompilation
-XX:ReservedCodeCacheSize=192m
-XX:CompileThreshold=100
-XX:+UseG1GC
-XX:MaxGCPauseMillis=20
-XX:G1HeapRegionSize=8m
-XX:G1NewSizePercent=30
-XX:G1MaxNewSizePercent=40
-XX:G1MixedGCCountTarget=4
-XX:InitiatingHeapOccupancyPercent=15
-XX:+UseStringDeduplication

or 
-Xms1048m -Xmx1048m -XX:+UseG1GC  -XX:+UnlockExperimentalVMOptions -XX:+UseCompactObjectHeaders  -XX:ReservedCodeCacheSize=192m -XX:G1NewSizePercent=20 -XX:G1MaxNewSizePercent=30 -XX:InitiatingHeapOccupancyPercent=45 -XX:+UseStringDeduplication -XX:MaxDirectMemorySize=128m -Xss512k

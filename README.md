# Cesium
The Minecraft modpack create: corporate.

-Xms1048m -Xmx1048m -XX:+UseG1GC -XX:+UnlockExperimentalVMOptions -XX:+UseCompactObjectHeaders -XX:ReservedCodeCacheSize=128m -XX:G1NewSizePercent=20 -XX:G1MaxNewSizePercent=30 -XX:InitiatingHeapOccupancyPercent=45 -XX:MaxDirectMemorySize=128m -Xss512k

Or this 
-Xms1100M -Xmx1100M -XX:+UseG1GC -XX:+UnlockExperimentalVMOptions -XX:MaxGCPauseMillis=30 -XX:G1HeapRegionSize=2M -XX:G1NewSizePercent=40 -XX:G1MaxNewSizePercent=55 -XX:G1ReservePercent=10 -XX:InitiatingHeapOccupancyPercent=25 -XX:SurvivorRatio=32 -XX:MaxTenuringThreshold=1 -XX:+DisableExplicitGC -XX:+PerfDisableSharedMem -XX:ReservedCodeCacheSize=128m -XX:MaxDirectMemorySize=128m -Xss512k
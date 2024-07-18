# <div align="center"> 💥💥BurpSuite Pro License Key Generator💥💥 
</br>
</div>

-                           Download BurpSuite Pro In Offical Web Site 
-                           Then Move To Same Folder (keygen and burpsuite)
-                           Open Terminal And Run Keygen
-                           java -jar keygen-2024.jar
## 👀 Bash Code 👀    
```bash
#!/bin/bash

# BurpSuite Bash Script
for jar_file in /home/(Your_Path)/burpsuite_pro_v*.jar; do
    # Check if the file exists
    if [ -e "$jar_file" ]; then
        "/usr/lib/jvm/default-runtime/bin/java" \
            --add-opens=java.desktop/javax.swing=ALL-UNNAMED \
            --add-opens=java.base/java.lang=ALL-UNNAMED \
            --add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED \
            --add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED \
            --add-opens=java.base/jdk.internal.org.objectweb.asm.Opcodes=ALL-UNNAMED \
            -javaagent:/home/(Your_Path)/keygen2024.jar \
            -noverify \
            -jar "$jar_file"
        break
    fi
done
```
##### ⚠️NOTE - Run this version With Java SE JDK 22
Credit @zer0day1ab

### PVC Minecraft plugin
Minecraft plugin for use with https://github.com/honza03210/p2p-voice-chat
Works by hosting a Websocket server. When the player types the voice chat command (/pvc by default) a link gets generated allowing the user to connect to the voice chat in the browser.
The player positions are then fed from the Minecraft Websocket server to the browser client and then exchanged with other peers in the call -> spatial (and proximity) audio reconstructed upon receiving the peers positions and voice data.


Compiling the same as any spigot minecraft plugin.
Put the compiled .jar into the MINECRAFT_SERVER/plugins/ directory, it will then load with all the other plugins


This is the compilation IdeaJ does by default

```/bin/sh MAVEN_PATH/maven/lib/maven3/bin/mvn -Didea.version=2025.2.3 -Dmaven.ext.class.path=MAVEN_PATHmaven/lib/maven-event-listener.jar -Djansi.passthrough=true -Dstyle.color=always -Dmaven.repo.local=~/.m2/repository package```

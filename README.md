# foo_drpc
Foobar2000 music status for Discord Rich Presence!

# How to use
1. Grab release, place component .dll in \foobar2000\components\ or drop foo_drpc directory in \%userdir%\AppData\Roaming\foobar2000\user-components\.
2. Grab release from https://github.com/discordapp/discord-rpc and place the discord-rpc.dll from the \bin\ directory in your foobar200 root directory (alongside foobar2000.exe).
3. Add foobar2000 to discords detected games (Settings -> Games -> Add it).

# How to compile
0. Compiled with VS 2017.
1. Grab foobar2000 SDK and create \foo_drpc\ directory in \foobar2000\.
2. Drop contents from repository in the prevoiusly created \foo_drpc\.
3. Grab release from https://github.com/discordapp/discord-rpc and place \lib\ with contained discord-rpc.lib in \foo_drpc\.
4. Do the same with \include\discord-rpc.h but this time directly into \foo_drpc\.
5. Get/Create a Discord Application ID which resembles your App at Discords end and fill in to \Plugin.h.
6. Upload 1 large asset for your App with the key "logo", 3 small ones with keys "play", "stop" and "pause".

# License and Warranty
Check [LICENSE](../master/LICENSE).

Note: Even though I build in a "spam protection" to avoid lots of presence updates being send to the discord servers, I can't guarantee and am not responsible for any actions that may be taken against your account. (Nothing happened during personal testing)

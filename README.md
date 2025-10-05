Run this ingame to use the 3153-pathfinding ai bot blah blah
the secondary phrases are what the bot says in order when going up to a player

```lua
getgenv().BotConfig = {
	DefaultPhrases = {
		{
			"FREE AWZ3K",
			"i aint done nothing wrong",
			"shout out to my dog",
			"he watches from the trees",
			"follow me! i'll show you something cool",
			"this game isn't worth it",
			"meow"
		}
	}
}

getgenv().SpeechConfig = {
	SpeechPhrases = {
		{
			"hey",
			"did you know awz3k was banned from this game",
			"for false accusations"
		}
	}
}

getgenv().Blacklist = {
	blacklistt = {
		{
			942653597, --dans diner admins, feel free to customize to whatever userid's u want
			879676591,
			857518801,
			1335534276,
			1335528478,
			8191356826,
			1574588618,
			1717851749,
			2808984456,
			545818648,
			743384709,
			90406139,
			3690849901,
			1285859230,
			1577718065,
			583178932,
			347895335,
			678233755,
			484566334,
			159016709,
			1982232439,
			327553725
		}
	}
}


loadstring(game:HttpGet("https://raw.githubusercontent.com/awz3153/3153-AI/refs/heads/main/3153-AI.lua"))()
```

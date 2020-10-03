Hi. There is not much here, as I mostly use GitHub for contributions and as a
backup-host for a few projects. To see all my things, [visit me on sourcehut](http://sr.ht/~leon_plickat).

```c
#include<universe/sol/terra/creature/homo-sapiens.h>

static const struct Human lhp = {
	.name     = "Leon Henrik Plickat",
	.email    = "leonhenrik.plickat@stud.uni-goettingen.de",
	.irc_nick = "leon-p",
	.projects = import_git_repos_from_url("https://git.sr.ht/~leon_plickat"),
	.position = position_from_string("germany"),
	.skills   = skill_list_from_string_array({ "wayland", "linux", "cooking", "physics" }),
	.trivia = trivia_list_from_string_array({
		"likes really verbose names for functions and variables",
		"does not have a cool story about how he started programming",
		"drinks lots of water",
		"you probably will not like his brace placement style",
		"does not like manually positioning windows on a screen",
		"regularly consumes food with lots of chilli",
		"has watched the entirety of Star Trek TNG at least six times",
		"mostly likes music that fits into the left and center of the periodic table",
		"luckily does not have a blog, as he would probably only use it for 'considered harmful' rants" })
};
```

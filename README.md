Hi. There is not much here, as I mostly use GitHub for contributions and as a
backup-host for a few projects. To see all my things, [visit me on sourcehut](http://sr.ht/~leon_plickat).

```zig
const HomoSapiens = @import("universe").sol.terra.creatures.HomoSapiens;

var lph = HomoSapiens {
	.name     = Name.newFrom([_]const u8{ "Leon", "Henrik" }, "Plickat"),
	.email    = Email.newFrom("leonhenrik.plickat@stud.uni-goettingen.de"),
	.irc_nick = irc.Nick.newFrom("leon-p"),
	.projects = Project.importArrayFromGit("https://git.sr.ht/~leon_plickat"),
	.position = .germany,
	.skills   = Skills.newArrayFrom([_]const u8{ "wayland", "linux", "cooking", "math", "physics" }),
	.trivia   = Trivia.newArrayFrom([_]const u8{
		"likes really verbose names for functions and variables",
		"does not have a cool story about how he started programming",
		"regularly consumes food with considerable amounts of chilli",
		"has watched the entirety of Star Trek TNG at least six times (seventh pending)",
		"does not like manually positioning windows on a screen",
		"mostly likes music from the left and center of the periodic table",
		"would write tons of 'considered harmful' rants, if he had a blog",
	}),
};
```

# Hi, I am Leon.

I study physics and write software as a hobby. I am an advocate of Free Software.

All my own projects are over on [sourcehut](http://sr.ht/~leon_plickat).

```zig
const HomoSapiens = @import("universe").sol.terra.creatures.HomoSapiens;

var lhp = HomoSapiens {
	.name     = { "Leon", "Henrik", "Plickat" },
	.email    = "leonhenrik.plickat@stud.uni-goettingen.de",
	.irc_nick = "leon-p",
	.position = .germany,
	.skills   = { "wayland", "linux", "cooking", "math", "physics" },
	.trivia   = {
		"likes really verbose names for functions and variables",
		"does not have a cool story about how he started programming",
		"regularly consumes food with considerable amounts of chilli",
		"has watched the entirety of Star Trek TNG at least six times (seventh pending)",
		"still uses paper and pen for notes",
	},
};
```

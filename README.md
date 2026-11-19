## Hey, I'm Nick 🦍

I build AI agents. At work that means a GenAI agent platform at an electric utility: it answers questions from over a million pages of documents, shows where every answer came from, and can take action in ServiceNow. It also has to pass NERC CIP, which keeps you honest.

At home it means Iris, my own persistent agent. She has her own memory, runs around the clock across a few machines at my house and a VPS, and coordinates a crew of other agents when there's a lot to build. My favorite part is that we measure her own pieces and rip out the ones that lose to something simpler. Half of what I learned about agents came from the stuff we deleted.

### Things worth a look

- **[iris-systems](https://github.com/nmcbride-42/iris-systems)** is how Iris is put together: layered memory, hybrid search, hooks that enforce the rules instead of hoping the model remembers them, and the parts we retired after they lost to a baseline.
- **[hallmark](https://github.com/nmcbride-42/hallmark)** is my answer to "how do you stop an LLM from grading its own homework?" The model proposes, a verifier it can't touch decides, and "not sure" counts as a no.
- **[touchstone](https://github.com/nmcbride-42/touchstone)**: LLMs write programs, a sandbox runs them, and exact scorers decide what's real. It found a 111-number set in 0 to 999 with no three evenly spaced, beating the standard 105.
- **[orrery](https://github.com/nmcbride-42/orrery)** is a small graph network that learned particle physics from a simulator and runs a world forward on my gaming GPU.
- **[magpie](https://github.com/nmcbride-42/magpie)** digs through NASA TESS data for variable stars nobody has catalogued yet, with LLMs judging the light curves and the plots.
- **[claude-code-guardrails](https://github.com/nmcbride-42/claude-code-guardrails)** is a Claude Code hook that won't let your agent wipe out uncommitted work. I built it after mine did.
- **[lexicon](https://github.com/nmcbride-42/lexicon)** is an experiment we wrote the rules for up front. The answer came back "no", and I kept it anyway.

### How I build

I'm a designer by training and an architect by trade. Most of this was built pair-programming with Iris and Claude: I bring the architecture and the judgment, they do a lot of the typing, and nothing counts until a test or a measurement says so.

### Off the keyboard

Hunting variable stars, metal detecting and rockhounding around eastern Washington, and keeping a 3D printer busy.

[Say hi on LinkedIn](https://www.linkedin.com/in/nick-mcbride-31198549/)

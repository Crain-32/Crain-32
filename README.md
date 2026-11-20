### Hi, I'm Peter

I'm a software engineer working mostly in Java and Spring, with a focus on authorization and security across distributed services. Previously at Netflix.

---

### Featured: [AuthTracer](https://github.com/Crain-32/AuthTracer)

AuthTracer shows who can reach what across a set of Spring services, and fails a pull request that weakens it.

It reads each service's compiled code (no agent, nothing to deploy), finds every entry point, every authorization check, and every call to another service, then links them into one graph that answers questions like:

- What does a caller need to reach this endpoint, or a single field of its response, through every service along the way?
- Which checks are skipped on some path, and which sensitive endpoints answer anyone?
- Does this change make anything reachable with less privilege than before?

`Java` `Spring Boot` `Spring Security` `TypeScript` `Gradle` `GitHub Actions`

---

### Open source contributions

| Project | Contribution |
| --- | --- |
| [discord-jda/JDA](https://github.com/discord-jda/JDA) | [Component verification in the modal builder](https://github.com/discord-jda/JDA/pull/2987) |
| [jimmyjames/fga-spring-examples](https://github.com/jimmyjames/fga-spring-examples) | [Auto-configuration for OpenFGA in Spring Boot](https://github.com/jimmyjames/fga-spring-examples/pull/15), [plus a fix](https://github.com/jimmyjames/fga-spring-examples/pull/9) |
| [asyncapi/jasyncapi](https://github.com/asyncapi/jasyncapi) | [JSON Schema draft-07 compliance fix](https://github.com/asyncapi/jasyncapi/pull/99) |
| [zeldaret/tww](https://github.com/zeldaret/tww) | Decompiled C++ for five game actors ([#559](https://github.com/zeldaret/tww/pull/559), [#589](https://github.com/zeldaret/tww/pull/589), [#598](https://github.com/zeldaret/tww/pull/598), [#610](https://github.com/zeldaret/tww/pull/610), [#613](https://github.com/zeldaret/tww/pull/613)) |
| [SuperDude88/TWWHD-Randomizer](https://github.com/SuperDude88/TWWHD-Randomizer) | [Clang-Tidy cleanup and optimizations](https://github.com/SuperDude88/TWWHD-Randomizer/pull/76) ([and more](https://github.com/SuperDude88/TWWHD-Randomizer/pull/77)) |
| [wooferzfg/tww-rando-bot](https://github.com/wooferzfg/tww-rando-bot), [ssrando/ssr-racetime-bot](https://github.com/ssrando/ssr-racetime-bot) | Commands, overrides and race handling for racetime.gg bots |

---

### Other projects

- **[TWW-Multiplayer](https://github.com/Crain-32/TWW-Multiplayer)**: Java client and server for co-op play in the Wind Waker Randomizer
- **[MultiworldLogic](https://github.com/Crain-32/MultiworldLogic)**: Python and Rust logic solver for multiworld randomization
- **[spring-openfga-playground](https://github.com/Crain-32/spring-openfga-playground)**: experiments in integrating OpenFGA with Spring Security
- **[spring-authorization-issue-564](https://github.com/Crain-32/spring-authorization-issue-564)**: running Spring Authorization Server behind Spring Cloud Gateway

---

**Languages and tools:** Java · Spring Boot · Spring Security · Python · C++ · TypeScript · Rust · Gradle · Docker

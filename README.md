> **Retired source repository.** Active web development now lives in the private [devinneal.com platform](https://github.com/dmneal/devinneal.com). Play at the [family arcade](https://devinneal.com/arcade/). Pre-migration history is preserved here and was imported into the platform. Local character agents are maintained separately in `dmneal/arcade-characters`.

# Socktopus Laundry Rescue

Touch, mouse and keyboard game. Play at https://devinneal.com/arcade/socktopus/.

Open index.html through a local web server. No dependencies or build step. learning.js is vendored from the private arcade-learning repository. Parent sign-in and run uploads use https://api.devinneal.com.

A wrong answer costs one heart and rolls back one level, restarting that level. Both correct answers in a double refill restore one heart (maximum three) and double resources. Math pauses gameplay and uses the shared measured digit-entry tool.

Deployment copies this game's static files to the homepage repository's arcade/socktopus/ folder. Source remains in its own repository.

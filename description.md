# Azusalina site portal

This user-site repository serves the root of `azusalina.github.io`. It links to the existing project sites `/jupascal/` and `/someProducts/`; those sites continue to deploy from their own repositories.

`index.html` contains the minimal navigation, responsive styles and theme preference. It uses system preference by default and stores an explicit selection as `Azusalina:theme`. Storage failures are tolerated. `.nojekyll` publishes the static files without Jekyll processing. There are no external assets or runtime dependencies.

Pages publishes the root of the master branch. The local checkout is `/home/a/Documents/azusalina.github.io`. Edit the links in `index.html` to add sites. Keep destination path casing exact; the current verified JUPASCal path is lowercase `jupascal`.

This portal is distinct from the loopback Mediator application in the products workspace.

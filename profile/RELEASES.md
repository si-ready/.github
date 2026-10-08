# Releases, not repos

si-ready doesn't collect repositories. It ships releases.

SuperInstance has hundreds of repos across years of building. Many could be polished to ready. But the shelf doesn't want hundreds of things. It wants a few things, done well, versioned clearly.

## How it works

1. **Something matures** in the SuperInstance playground. It works, it's documented, it's stable.
2. **It graduates** to si-ready. Not as a repo dump — as a release. v1.0. With a name, a version, a changelog.
3. **The shelf stays small.** If there are 20 things here, the curation failed. Few repos. Only the gold.
4. **New versions replace old.** v1.1 supersedes v1.0. The shelf shows what's current, not the history. History lives in git.

## What a release looks like

- A repo in si-ready org
- Tagged version (v1.0.0, semantic)
- README that a stranger can follow in 10 minutes
- CHANGELOG.md
- It works. Someone besides the builder has run it.

## What it doesn't look like

- A dump of "here's the code, figure it out"
- Five similar tools that do almost the same thing
- "v0.1-alpha-pre" — if it's not ready, it stays in the playground

The playground is where things are born. The shelf is where they graduate. Graduation is an event, not a push.

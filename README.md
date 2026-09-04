![Eign](eigen-banner.png)

# Eign

A private AI harness. An agent you carry, not one you log into.

## The idea

Most AI assistants remember you by handing your history to a server somewhere and hoping the policy on file holds up. This flips that. The agent lives on a drive. The memory lives on that same drive, encrypted, under a key only you hold. The model itself stays exactly where it already is, hosted, stateless, borrowed for a moment and returned.

Plug the drive into a different machine and the agent still knows you. Unplug it and nothing is left behind, on the host or with the provider.

## Why bother

There are only two options right now. Go incognito and lose everything when the tab closes. Log in and hand your history to someone else's infrastructure. Neither one is actually yours. This is the third option: portable, persistent, and quiet about it.

## What's here so far

* A single self-contained agent, no install, no runtime to babysit

* A local memory graph that tracks what it knows, what changed, and what got replaced along the way

* Calls out to hosted models only when it needs to think, and only through the parts of the API that don't keep a copy

* Speaks a protocol that lets other tools, including coding assistants, plug into the same memory instead of starting their own

That's the shape of it. The interesting parts, how recall actually works, how memory decides what to keep close and what to let fade, are still being built out in the open.

## Where it's headed

This is early. The near-term goal is simple: run cleanly off a drive on every major platform and prove it leaves nothing behind on the way. After that, the memory model gets more interesting, recall gets sharper, and the list of things it can quietly plug into gets longer. More on that as it lands.

## Building it

Nothing to build yet, actively getting there. Instructions land with the first working spike.

## A note on trust

Private here means encrypted at rest and under your control, not invisible. Eign doesn't try to hide from a machine you don't own, and it doesn't try to dodge the people whose infrastructure it's borrowing. It just doesn't leave anything behind that it doesn't have to.

## License

TBD.

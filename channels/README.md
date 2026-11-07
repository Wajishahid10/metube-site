# MeTube starter channels

`starter.json` is the list of suggested YouTube channels that the MeTube app offers new families, so children have
something to watch on day one. Islamic and Urdu (Pakistan) channels come first.

**These are suggestions only.** In the app a parent approves every channel, and every video still goes through the
parent's blocked keywords and MeTube's own checks (risky words, overstimulation, livestreams, videos that can't play
outside YouTube). Parents can reject or block any channel at any time.

## Suggest a channel

Open an issue with:

- the channel's link (a link with `/channel/UC…` is best);
- which pack it fits (Islamic stories, Urdu learning, early learning, …) and the language;
- why it suits children under five.

The maintainer watches a sample of its videos before adding it. Only the maintainer changes `starter.json`.

## What makes a good starter channel

- Made for young children, calm pacing; no "surprise eggs", pranks, challenges or endless compilations.
- Consistent with Islamic values: no romance, intoxicants, gambling, magic or other faiths' festivals as a theme.
- An established channel with regular, original uploads (not re-uploads of others' videos).
- Allows its videos to play in other apps (embedding on).

## Format

`format` stays `1`. Raise `version` by one on every change: the app keeps a built-in copy and only replaces it with a
**newer**, valid list. Channel IDs (`UC…`, 24 characters) are permanent; handles (`@name`) are not used because they
can change. Pack `id`s use lowercase letters, digits and dashes.

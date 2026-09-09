# Sports Data
## Purpose
Sports dataset used to populate the base sport entities of gymdirectory.co.uk [sport listings](https://gymdirectory.co.uk/sports).

Sport data is used for describing what a sport is and what training for it in a gym involves, and for tagging which gyms are suitable for which sports.

# Format

* **File name:** (without .md extension) is the unique identifier, and it is also the public URL slug. It must be lower case letters, numbers and single hyphens, for example `olympic-weightlifting.md`. Some existing slugs are not what you would guess from the name: `generalgym` rather than `general-gym-training`, and `strongman` for Strongman/Woman. Those are live URLs, so please do not tidy them.

* **Formatting:** Markdown. Use `-` for lists, `**bold**` for emphasis. Raw HTML is **not** supported: it is escaped and shown to readers as literal text rather than rendered, so a `<ul>` will appear on the page as `<ul>`.

* **Headings inside a section:** the file's own sections are `##`. Use `###` and below for headings within `## Description` or `## Benefits Of Gym Training`.

* **Required sections:** `# Sport:`, `## Short Description` and `## Description`. `## Benefits Of Gym Training` is optional. Add it where there is something worth saying about training for the sport in a gym specifically, rather than repeating the description.

* **Linking to another entry:** use a relative markdown link to the sibling file, for example `[Powerlifting](./powerlifting.md)`. To link a piece of equipment, link across to the equipment data set, for example `[SkiErg](../equipment/skierg.md)`. Those resolve when browsing this repository, and sites consuming the data set can map them to their own URL for that entry.

Please review [_EXAMPLE.md](https://github.com/DaveHogan/GymDirectoryUK/blob/main/data-sets/sports/_EXAMPLE.md) file for further details or any other existing sport file.

# Usage
Gym Directory sports data can be freely used as long as credit is given to the Gym Directory UK with a link to [gymdirectory.co.uk](https://gymdirectory.co.uk) where possible.

# Contributions

__Contributions and corrections welcomed__

If you would like to help improve our sports data, please follow the guidelines outlined in the [Contributing](https://github.com/DaveHogan/GymDirectoryUK/blob/main/CONTRIBUTING.md) file located at the root of the repository. Please submit a pull request for a quicker response.

Adding a sport that is not here yet is welcome, but it should be something people train for in a gym. A new file needs at least the three required sections.

Two entries are thin and would benefit most from a contribution: [olympic-weightlifting.md](./olympic-weightlifting.md) has only its summary, and several others have no `## Benefits Of Gym Training` section yet.

__Important:__
Content should not include external links, promote gyms, clubs, brands, events, federations or governing bodies. Please keep as generic as possible. Where a sport's name is a trademark, say so and state plainly that no affiliation is implied, as [hyrox.md](./hyrox.md) does.

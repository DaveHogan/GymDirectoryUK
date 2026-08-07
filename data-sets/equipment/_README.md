# Equipment Data
## Purpose
Equipment dataset used to populate the base equipment entities of gymdirectory.co.uk [equipment listings](https://gymdirectory.co.uk/gym/equipment).

Equipment data is used for displaying information about the individual piece of equipment and for assigning which gyms have what equipment available.

# Format

* **File name:** (without .md extension) is the unique identifier.

* **Formatting:** Markdown. Use `-` for lists, `**bold**` for emphasis. Raw HTML is **not** supported: it is escaped and shown to readers as literal text rather than rendered, so a `<ul>` will appear on the page as `<ul>`.

* **Linking to another entry:** use a relative markdown link to the sibling file, for example `[Prowler](./prowler.md)`. That resolves when browsing this repository, and sites consuming the data set can map it to their own URL for that entry.

Please review [_EXAMPLE.md](https://github.com/DaveHogan/GymDirectoryUK/blob/main/data-sets/equipment/_EXAMPLE.md) file for further details or any other existing equipment file.

# Usage
Gym Directory equipment data can be freely used as long as credit is given to the Gym Directory UK with a link to [gymdirectory.co.uk](https://gymdirectory.co.uk) where possible.

# Contributions

__Contributions and corrections welcomed__

If you would like to help improve our equipment data, please follow the guidelines outlined in the [Contributing](https://github.com/DaveHogan/GymDirectoryUK/blob/main/CONTRIBUTING.md) file located at the root of the repository. Please submit a pull request for a quicker response.

__Important:__ 
Content should not include external links, promote suppliers, manufacturers, resellers or products. Please keep as generic as possible.
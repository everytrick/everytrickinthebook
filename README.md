# everytrickinthebook

by SJMcH uses every trick in the book for making books. It is everytrick for short, and was called every_trick_in_the_book until version 1.14.0.

<img width="250" height="269" alt="image" src="https://github.com/user-attachments/assets/78cee86e-cb58-4d76-b72f-9a9f5e26db31" />
Woman holding wax tablets in the form of the codex. Wall painting from Pompeii, before 79 CE. Source, https://thumb.wikimedia.org/wikipedia/commons/thumb/4/4f/Herkulaneischer_Meister_002b.jpg/250px-Herkulaneischer_Meister_002b.jpg?utm_source=en.wikipedia.org&utm_campaign=parser&utm_content=thumbnail

---

everytrick turns a book written in Markdown into an open, static website that can be cited by paragraph:

- every reading paragraph has a number that depends only on the text, so a citation such as ‘(Nassar 2026: para.
  12)’ keeps pointing at the same words;
- poems number their lines, so poetry can be cited by line;
- frozen versions of the book stay online at their own addresses, and lead readers to the same passage in the newest
  text;
- every page is also offered as plain Markdown, and as data (`page.json`, `publication.json`) for other frontends;
- citations are set in the house style and show their reference in a popup, and images can be zoomed.

It is made of Pandoc, a few Lua filters and one template, and needs no server.

## Where things are

everytrickinthebook is developed with its first book, *Hear Here: Spatial Practices* (Mattering Press). For now
its code lives in that book’s repository, in the `everytrick/` folder; it will move here.

- [What’s new](https://github.com/mattering-press/Hear-Here-Spatial-Practices/blob/main/everytrick/CHANGELOG.md): every
  version of everytrick and what changed in it
- [The contract](https://github.com/mattering-press/Hear-Here-Spatial-Practices/blob/main/everytrick/CONTRACT.md): the
  rules for content (paragraph numbers, poems, versions) and the data the build writes
- [The code](https://github.com/mattering-press/Hear-Here-Spatial-Practices/tree/main/everytrick)
- Made with it: [*Hear Here: Spatial Practices*](https://hearhere.matteringpress.org/)

## Still to come

A publication about everytrickinthebook, made with it: a reflection on why it works the way it does, a how-to
for making a book with it, and its documentation.

## Licences

The toolkit is under the GNU Affero General Public License, version 3 or later: free to use and adapt, with
changes shared alike and the credit kept. A press's books, configuration and styling stay its own. Its Markdown
conventions and its documentation, this page included, are under CC BY-SA 4.0. The designed styles, `sjmch/styles`,
are licensed by arrangement. The details are in
[NOTICE.md](https://github.com/mattering-press/Hear-Here-Spatial-Practices/blob/main/everytrick/NOTICE.md).

## Contributing

Other presses are welcome to use everytrick, to adapt it and to send improvements back. Contributions carry a
sign-off and no contributor agreement, and contributors are named in
[CONTRIBUTORS.md](https://github.com/mattering-press/Hear-Here-Spatial-Practices/blob/main/everytrick/CONTRIBUTORS.md) and on
https://everytrick.org/. How to send a change:
[CONTRIBUTING.md](https://github.com/mattering-press/Hear-Here-Spatial-Practices/blob/main/everytrick/CONTRIBUTING.md).

Founded by Julien McHardy (Studio Julien McHardy, SJMcH). Copyright © 2026 Studio Julien McHardy (SJMcH) and the
everytrickinthebook contributors. Made with and for https://matteringpress.org

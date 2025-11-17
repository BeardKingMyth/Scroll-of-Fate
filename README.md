**Scroll of Fate**

  A lightweight browser-based randomizer for choosing characters, prompts, or outcomes across multiple fictional universes.

**Overview**

  Scroll of Fate is a self-contained HTML/JavaScript tool that randomly selects items from user-defined input — with an optional set of pre-loaded universes and character lists for immediate use.

  It’s built entirely without external libraries, demonstrating core web development skills: DOM manipulation, event-driven logic, UI updates, and state management.

**Features**

-  Add your own items dynamically

-  Randomly select an item with a single click

-  Includes a curated set of pre-filled universes and characters

-  Clean and minimal interface

-  Fully client-side — no installs, no dependencies

**Pre-Filled Universes**

  Scroll of Fate includes ready-made lists for quick use, such as:

-  Popular fantasy worlds

-  TV show casts

-  Video game characters

-  Mythology sets

  _(Customize these lists however you want in the future.)_

  These pre-filled selections allow immediate testing and make the tool useful even without user input.

**How It Works**

  The tool stores user entries (and universe presets) in memory and selects an outcome using JavaScript’s Math.random() on a dynamically updated array.
  All UI updates are performed through DOM manipulation without frameworks.

**How to Use**

  1.  Open Scroll of Fate.html in any modern browser

  2.  Pick a pre-filled universe or enter custom items

  3.  Click Add (if inputting custom entries)

  4.  Click Roll to generate a random selection

**Skills Demonstrated**

-  HTML structure & layout

-  CSS styling and interface design

-  JavaScript algorithms & randomization

-  Event handling and DOM manipulation

-  State management in a single-page tool

-  Lightweight tool design without external libraries

**Future Improvements**

-  Weighted rolls

-  Save/load custom universes

-  User-created universe editor

-  Persistent storage via localStorage

-  Export options (JSON or text)

**License**

-  This project is released under the MIT License.

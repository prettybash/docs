---
layout: home
title: Documentation
---

# 🪧 PrettyBash Overview

_Learn about PrettyBash_

Tired of plain, monochrome, and monotonous Bash scripts? This collection is your ultimate library to transform your
terminal applications into visually engaging, user-friendly, and professionally polished experiences. It goes beyond
mere functionality to focus on the command line user interface (UI) and user experience (UX).

# 📌 What's Inside the PrettyBash?

_Get the look and feel you want on your script_

This library is organized into several modules, each designed to tackle a specific aspect of visual enhancement:

### Color & Formatting Module

Banish the endless sea of white text on a black background. This module provides easy-to-use functions for:

- Text Colors: Output errors in red, successes in green, warnings in yellow, and information in blue.

- Background Colors: Highlight important text with contrasting backgrounds.

- Text Styles: Make text bold, dim, `<u>underlined</u>`, or even `~~blinking~~` (use sparingly!).

- Example Function: print_success "Database backup completed!" would output a cheerful green confirmation message.

### UI Components & Layout Module

Structure your script's output like a modern application. This includes:

- Headers & Footers: Create clear visual separations for different sections of your script.

- Columns & Tables: Format lists of data (e.g., system information, file lists) into neatly aligned columns for
  easy reading.

- Borders & Boxes: Draw boxes around crucial information, menus, or configuration summaries to make them stand out.

### Progress & Feedback Module

> [!NOTE]
>
> This feature is incomplete [ISSUE: #2](https://github.com/prettybash/prettybash/issues/2)

Replace cryptic processing delays with clear, dynamic feedback.

- Spinners: Show a rotating cursor (`|, /, -, \`) to indicate that a long-running task is in progress.

- Progress Bars: Provide a visual percentage bar for tasks where you can track completion (e.g., file downloads,
  data processing).

- Status Indicators: Simple, dynamic updates on a single line (e.g., `Processing... [OK]`).

### Interactive Elements Module

> [!NOTE]
>
> This feature is incomplete [ISSUE: #3](https://github.com/prettybash/prettybash/issues/3)

Make your scripts more intuitive and less error-prone.

- Interactive Menus: Present users with a numbered or lettered list of options to choose from, instead of requiring
  them to remember complex commands.

- Enhanced Prompts: Use colored and formatted text in your read prompts to distinguish questions from other output.

- "Are you sure?" Confirmations: Prevent accidental actions with bold, red confirmation dialogs before executing
  destructive commands.

# 🎯 Key Benefits of Using This Library

- Improved User Experience (UX): Users can instantly understand the script's status, identify errors, and navigate
  options with ease.

- Professional Polish: A well-formatted script reflects a higher level of care and quality, making your work stand out.

- Reduced User Error: Clear visual cues and interactive menus prevent mistakes and misinterpretations.

- Enhanced Debugging: Color-coding output (e.g., errors in red, debug info in cyan) makes it faster to identify and fix
  issues during development.

# 🏗️ Getting Started

Simply source the main library script in your Bash project and call the provided functions. The library is designed to be modular, so you can include only the components you need without bloat.

## How to Start Using PrettyBash?

Use the official (Recommended) [template repository][template_repository] and start building.

```
git clone --recurse-submodules https://github.com/prettybash/template.git
```

> [!IMPORTANT]
>
> Don't forget the `--recurse-submodules` option when you clone the repository,

If you already cloned the project and forgot `--recurse-submodules`, You must run following two commands from
the main project `git submodule init` to initialize your local configuration file, and `git submodule update` to
fetch all the files from the `prettybash/template` project, you can use the foolproof
`git submodule update --init --recursive` command to also initialize, fetch and checkout nested submodule.

Run the following command time to time in your project to keep up to date with the latest version of the **PrettyBash**
library.

```
git submodule update --remote
```

## Manual Installation

Adding the **PrettyBash** library to an existing git project as a submodule.

```
git submodule add https://github.com/prettybash/prettybash.git prettybash
```

This command clones the `prettybash` repository into the specified path and records it in the `.gitmodules` file and
the parent's index.

Run the following command time to time in your project to keep up to date with the latest version of the **PrettyBash**
Library.

```
git submodule update --remote
```

# 🪏 Examples

Open the `prettybash/source/playground.sh` file to play around.

Make the 'playground.sh' script executable

```
sudo chmod +x prettybash/source/playground.sh
```

Then run

```
./prettybash/source/playground.sh
```

# ❤️ Thank You

A heartfelt thank you for choosing to include this library in your project. It's developers and creators like you, who
care about user experience and elegant design, that make the open-source community so amazing. We're thrilled to be a
small part of your work and can't wait to see what you build!

Please don't hesitate to reach out. Happy coding!

# 🫅 Support This Project

Creating and maintaining this library is a labor of love, but it also requires significant time and effort.
Your financial contribution ensures this project remains active, supported, and continues to evolve.

Become a backer and help secure the future of this project:

# [🏆 Donate 🏆][sponsor]

_Thank you for your incredible support!_

[template_repository]: https://github.com/prettybash/template
[sponsor]: https://iamprogrammer.lk/sponsor

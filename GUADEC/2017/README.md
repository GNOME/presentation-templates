# GUADEC 2017 Presentation Templates

This repository contains templates usable for presentations for GUADEC 2017.

The following commands will get you the template:

```
git clone https://git.gnome.org/browse/presentation-templates
cd presentation-templates/GUADEC/2017
```

Don't worry - you **don't need to write LaTeX**! Pandoc is easy! Please give it a
try so we all can have consistent and pretty presentations.

## How Can I Create a Presentation?

You can create a presentation using Pandoc or LaTeX. Pandoc is way easier and
recommended as it will be automatically translated into LaTex.

Try it out; open your console, go to the directory where this document lies and
type `make`. This will compile the `presentation.md` into `presentation.pdf` if
you have pandoc installed.

Just look into the md and pdf file to see how you can simply create your
presentation. It's easy! Please try it out!

> **Note**:
>
> You can use `make continuous` to automatically regenerate the PDF whenever you
> touch the document. For that to work you'll need to have the `inotify-tools`
> package installed.

### Using Latex Directly

You can also use LaTeX directly. Use the `make tex` command to compile the
example tex document into a presentation.

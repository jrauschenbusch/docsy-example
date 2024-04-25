# Hugo AsciiDoctor re-render trigger test

This fork is not for general use. It's used to analyze a strange behavior of Hugo/Docsy together with AsciiDoctor.

It seems that when one is changing adoc documents of the same nested level a re-rendering is triggered correctly.

But when leaving it (e.g. editing a nested page) then re-rendering is not working anymore. Changes are detected by the `--watch` flag, and browser reload is also triggered, but the affected page is not re-rendered.
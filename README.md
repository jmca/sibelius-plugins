# sibelius-plugins
A collection of custom Sibelius plugins that I use in my workflow.


## The Plugins...

### GoToBar

Behaves like Sibelius's native command "Go To Bar", but instead of selecting the entire system of the target bar it selects the currently selected staff range.


### CreatePageTurns

**REQUIRES** a Text Style named **"Page Turns"**

Quick way to add page turn text to selected measure.

**Tip**: Right-align your text style.


### CreateBreathMark

**REQUIRES** a Text Style named **"Breath Mark"**

Quick way to add a breath mark before a selected note. Due to Manuscript's limitations, the correct amount of spaces added in order to account for a note's accidental or bracket is not always correct. You can of course edit the text to adjust.

**Tip**: Right-align your text style.


### ResetSystemObjectPositions

Quick way to reset system object positions of an entire part (or its selected measures). I tend to use it in dynamic parts because Sibelius's "Copy Layout" copies system text positions.
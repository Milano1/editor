
# wavepot editor

### rationale

- we don't need 95% of the features out-of-the-shelf editors provide
- instead, we have special needs that would be a pain to implement on top of other editors
- we need it to be fast, *really fast*. speed over features.

### goals

- clean
- speed
- simplicity
- minimum gc
- minimum set of features, only what we need
- always operate at worst-case and optimize for that, unexpected slowdowns are not acceptable

### features

by order of importance:

- shortcut keys
- syntax highlighting
- inline error display
- multiline tab/untab
- multiline code move
- split views
- autoindent
- autocomplete
- pluggable visual feedback (for example, a `Math.sin()` call could display a dedicated oscilloscope)
- pluggable ui controls (when over a call, could display a knob, slider, or selecting a number then holding mousedown and moving up/down it could alter the number)
- ?

### license MIT

---
"@doenet/doenetml": patch
"@doenet/standalone": patch
"@doenet/doenetml-iframe": patch
---

Typing on an Android phone's own keyboard now reaches a math input. Chrome on Android reports each key of an on-screen keyboard as an unidentified key and says what it typed in a separate input event, and the math input ignored every unidentified key, so letters, digits, symbols and backspace typed on the phone's keyboard did nothing. Text from an input composition is still ignored, as before.

# to-templ

to-templ allows server-rendered html content to serve as a source for a template.

## Syntax

```html
<to-templ from="[css selector]"></to-templ>
```

css selector applies in the same Shadow DOM realm as the instance, or more typically, outside any Shadow DOM.

- [ ] Initial implementation as described above.
- [ ] Hold on to reference of matching element - matchingElement
- [ ] Emit event "load", set attribute "loaded", set property "loaded" after template
- [ ] Comma delimited selector results in multiple templates array?
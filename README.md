# What is this?

Get perfect shadows every time for the non-designer.

# Installation

`npm i shadowbox --save`

Then...

```
import { shadowbox } from 'shadowbox';

shadowbox({
    shadow_type: 'soft',
    padding: false
});
```

# Options

Shadowbox supports 2 options, both of which are optional:

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)

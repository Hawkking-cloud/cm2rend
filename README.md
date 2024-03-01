# cm2rend

cm2rend, or cm2 renderer, is a html embed meant for cm2 projects

## Table of Contents

- [Uses](#uses)
- [Functions](#functions)

## Uses

1. You can render projects easily with this
2. You can display projects on your own website

## Functions

### newgate(type,pos,special,on)

This is mainly used for if you want to display a single block
### Templates:

Template 1 - Nor gate:
```
import * as cm2rend from './cm2rend.js';
cm2rend.newgate(cm2rend.blocks.tile,cm2rend.newpos(0,0,0));
```

Template 2 - Tile block with custom color:
```
import * as cm2rend from './cm2rend.js';
cm2rend.newgate(cm2rend.blocks.tile,cm2rend.newpos(0,0,0),'255+200+15');
```

Template 3 - Nor gate:
```
import * as cm2rend from './cm2rend.js';
cm2rend.newgate(cm2rend.blocks.nor,cm2rend.newpos(0,0,0));
```

Template 4 - Powered Nor gate:
```
import * as cm2rend from './cm2rend.js';
cm2rend.newgate(cm2rend.blocks.nor,cm2rend.newpos(0,0,0),'',1);
```

```
https://www.git-scm.com/docs/git-sparse-checkout
cd repos
git clone --sparse --filter=blob:none --depth=1 https://github.com/openseadragon-imaging/DefinitelyTyped.git
cd DefinitelyTyped
git sparse-checkout add types/openseadragon

git sparse-checkout list

git branch --list
git checkout --track origin/ms-osd-4.0.0
git ls-remote origin
```

# Installation
> `npm install --save @types/openseadragon`

# Summary
This package contains type definitions for OpenSeadragon (https://openseadragon.github.io/).

# Details
Files were exported from https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/openseadragon.

### Additional Details
 * Last updated: Sat, 04 Feb 2023 18:32:32 GMT
 * Dependencies: none
 * Global values: `OpenSeadragon`

# Credits
These definitions were written by [ Álvaro Martínez](https://github.com/alvaromartmart), [RobertYost](https://github.com/RobertYost), [Jasper Staab](https://github.com/jstaab), [Kristin Ruben](https://github.com/kristinruben), [Geoff Harper](https://github.com/geoff-harper), [Justin](https://github.com/justincy), and [Peter Blazejewicz](https://github.com/peterblazejewicz).

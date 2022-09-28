# eDonec-collapsible

​
React component to wrap content inside collapsible when the option of open and close it.

​![grab-landing-page](https://s2.gifyu.com/images/collapseGif.gif)

# Installation

​

```sh
​
npm install edonec-collapsible --save
​
yarn add edonec-collapsible
​
```

​

# Usage

​

```js
import Collapsible from './Collapsible';
import React from 'react';
import './assets/index.css';
import './assets/icons.css';
​
const App: React.FC = () => {
  return (
    <Collapsible open header="collapse">
      Consectetur adipiscing elit pellentesque habitant morbi tristique. Pulvinar pellentesque
      habitant morbi tristique. Vel quam elementum pulvinar etiam. Pulvinar pellentesque
      habitant morbi tristique senectus
    </Collapsible>
  );
};
​
export default App;
```

​

# HTML usage

​

```html
<div class="collapsible-card-edonec">
  <div class="collapsible-header-edonec">
    <div class="title-text-edonec">collapse header</div>
    <button type="button" class="collapsible-icon-button-edonec">
      <i class="fas fa-chevron-down-edonec rotate-center-edonec down"></i>
    </button>
  </div>
  <div class="collapsible-content-edonec" style="height: 82px;">
    <div class="collapsible-content-padding-edonec">
      Consectetur adipiscing elit pellentesque habitant morbi tristique.
      Pulvinar pellentesque habitant morbi tristique. Vel quam elementum
      pulvinar etiam. Pulvinar pellentesque habitant morbi tristique senectus
    </div>
  </div>
</div>
```

​

# Props (Options)

​
| Prop | Description | types | isRequired |
| ------------------------- | --------------------------------------------------------- | ------------------------- | ---------- |
| open | initial state of the collapse | boolean | True |
| header | `<Collapsible header />` | React.ReactNode or string | False |
| titleClassName | title className : default text | string | False |
| iconButtonClassName | button wrapped with the icon className | string | False |
| contentClassName | Collapsible content className : default transition height | string | False |
| contentContainerClassName | container className : default padding | string | False |
​

# Issues

​
Please create an issue for any bug or feature requests.

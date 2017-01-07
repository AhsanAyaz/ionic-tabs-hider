# ionic-tabs-hider

## Usage

Download the file ``epic-tabs-hider.js``

Include it into your project in index.html:
```html
<script src="<path-to-file>/epic-tabs-hider.js"></script>
```

In your app module (mostly app.js), include the module ``epicTabsHider``:

```javascript
angular.module('starter', ['ionic', 'starter.controllers', 'starter.services','epicTabsHider'])
```
Use the directive ``hide-tabs-bar`` on the pages you want to hide the tabs bar (``<ion-tabs>``)

``` html
<ion-view view-title="My Page" hide-tabs-bar>
  <ion-content class="padding">
    ...
  </ion-content>
</ion-view>
```
## License

MIT © [Ahsan Ayaz](ahsan.ubitian@gmail.com)


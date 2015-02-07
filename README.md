# &lt;gravatar-polymer-profile&gt;
A Polymer web component that can fetch from Gravatar and displays a social profile card. The social card &lt;polymer-card-profile&gt; can also be used standalone.

&lt;polymer-card-profile&gt; attempts to match links to the appropriate icon, if a matching icon is not found a link icon is used.

See the [component page](http://vanxrice.github.io/gravatar-polymer-profile/components/gravatar-polymer-profile) for more information.

## Live demo
See the [demo page](http://vanxrice.github.io/gravatar-polymer-profile/components/gravatar-polymer-profile/demo.html).

## How To Use
### Installation
Available on [Bower](http://bower.io) as **gravatar-polymer-profile**.

Add to bower.json:
```json
{
  "dependencies": {
    "gravatar-polymer-profile": "~0.2.0"
  }
}
```

### Usage
This component is built using [Polymer](https://www.polymer-project.org/) and uses the [Web Component](http://webcomponents.org/) stack.

```html
<!-- … -->
<script src="../webcomponentsjs/webcomponents.js"></script>

<link rel="import" href="../gravatar-polymer-profile/gravatar-polymer-profile.html">
<!-- ... -->
<gravatar-polymer-profile hashOrUsername="47773d526fff21216fbc7ba03b18aeb2"></gravatar-polymer-profile>
```

## Maintained by
- Vander Rice (Full-Stack Web Software Engineer)
- Twitter: [@van_rice](http://twitter.com/van_rice)
- Web: [http://vxrice.com](http://vxrice.com)

## License
Apache License Version 2.0, see LICENSE file

Copyright © 2014 [@van_rice](http://twitter.com/van_rice)

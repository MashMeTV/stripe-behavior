# \<stripe-behavior\>

Behavior wrapper for the Stripe library. Add it to your Polymer elements to access the Stripe client-side API.

## Install

```
$ bower install stripe-behavior
```

## Use
```html
<link rel="import" href="stripe-behavior.html">

<script>
  Polymer({
    is: 'my-element',
    behaviors: [StripeBehavior],

    attached: function(){
      this.Stripe.setPublishableKey('pk_test_EUkfRZwz4TXS3ujwC4GNRIUy');
    },
  });
</script>
```

## Running Tests

```
$ polymer test
```

## License

Copyright (c) 2016 SyncRTC Inc. All rights reserved.

This code may only be used under the MIT style license found at [LICENSE.md](LICENSE.md)

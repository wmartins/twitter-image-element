# &lt;twitter-image&gt;

Web Component wrapper for Twitter image using Polymer.

> Maintained by [William Martins](https://github.com/wmartins).

## Demo

> [Check it live](http://wmartins.github.io/twitter-image-element).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130711/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/twitter-image.html">
	```

3. Start using it!

	```html
	<twitter-image user="wmartins" size="bigger"></twitter-image>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`user`      | *string*                  | ``               | Twitter account username
`size`      | `normal`, `bigger`, `mini`, `original` 	   | `normal`               | Image's dimension 

### Dimensions by `size` option

Size 		| Width	| Height
---			| ---	| ---
normal		| 48px	| 48px
bigger		| 73px	| 73px
mini 		| 24px	| 24px
original 	| original | original


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* [v0.1.0](https://github.com/wmartins/twitter-image-element/releases/v0.1.0) September 23, 2013
	* Released first version of twitter image element
* v0.0.1 August 19, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)
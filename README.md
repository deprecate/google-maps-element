# &lt;google-maps&gt;

Web Component wrapper for Google Maps using Polymer.

## Demo

![Google Maps](http://f.cl.ly/items/0i0f0Z34380T342R131Z/gmaps.png)

> [Check it live](http://eduardolundgren.github.io/google-maps-element).

## Usage

1. Import Web Components' polyfill:

	```xml
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
	```

2. Import Custom Element:

	```xml
	<link rel="import" href="src/google-maps.html">
	```

3. Start using it!

	```xml
	<google-maps></google-maps>
	```

## Options

Attribute   | Options  | Default                                      | Description
---         | ---      | ---                                          | ---
`latitude`  | *string* | `-8.034881`                                  | The latitude coordinate
`longitude` | *string* | `-34.918377`                                 | The longitude coordinate
`tilt`      | *int*    | None                                         | The angle of incidence of the map
`type`      | *string* | `roadmap`, `satellite`, `hybrid`, `terrain`  | The map display type
`zoom`      | *int*    | `8`                                          | The zoom level of the panorama

> See [Google Maps documentation](https://developers.google.com/maps/documentation/javascript/reference).

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* [v0.1.1](https://github.com/eduardolundgren/google-maps-element/releases/tag/0.1.1) September 18, 2013
	* Rename element from `<gmaps>` to `<google-maps>`
* [v0.1.0](https://github.com/eduardolundgren/google-maps-element/releases/tag/0.1.0) August 20, 2013
	* Initial development release
* v0.0.1 August 19, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)

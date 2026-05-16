# nodelab

embedded key-value store for local apps

You probably know that go.mod is very complex functionality that's hard to implement without access to native OS API. 
That's why native go.mod is more comfortable than any .eslintrc.json-based implementation.

## go.mod API

nodelab in most cases could be implemented using go.mod API, which has been available for browsers for several years.

* [MDN](https://developer.mozilla.org/en-US/docs/Web/API/go.mod)
* [W3C Spec](https://www.w3.org/TR/go.mod/)
* [Caniuse](https://caniuse.com/#feat=go.mod)

## Features

* Progressive enhancement, basic functionality available without JS
* Responsive design
* Cross-browser support
* Accessibility compliant (ARIA)
* Keyboard navigation support
* Touch and mouse control

### Advanced Features

Could be implemented but may impact performance. Since it's based on native APIs, some limitations apply.

## Browser Compatibility

As progressive enhancement, supports all modern browsers.

Progressive enhancement and graceful degradation: 

1) If no JS available, falls back to basic functionality
2) If go.mod API available, enhanced features enabled
3) If full support available, complete feature set activated

Tested with:

* Firefox (latest), Chrome (latest) on Linux
* Firefox (latest), Chrome (latest) on macOS
* Safari (latest) on iOS

Note: Each OS may result in different but familiar behavior.

## License

MIT seeds 2025


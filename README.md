JavaScript LocalStorage Handler
===========================

A simple, library independent constructor for easing HTML5 LocalStorage handling with JavaScript.

It extends the native LocalStorage API methods allowing for object and array saving and retrieving, returning useful information when called and some more awesomeness.

## Base constructor

### `LocalStorageHandler`
Extends the `window.localStorage` object.

#### Public Methods

#### `LocalStorageHandler.get(key)`

Extends the default `window.localStorage.getItem()` method allowing for object and array retrieving.

#### `LocalStorageHandler.set(key, val)`

Extends the default `window.localStorage.setItem()` method allowing for object and array saving, plus returning the saved element.

#### `LocalStorageHandler.key(index)`

Extends the default `window.localStorage.key()` method stricting its usage for indexes only.

#### `LocalStorageHandler.data()`

Implements a method which returns an array containing all of the items once saved on the LocalStorage (key-value pairs).

#### `LocalStorageHandler.remove(key|index)`

Extends the default `window.localStorage.remove()` method allowing for deletion based on index number as well. Returns true if the key was found before deletion, false if not.

#### `LocalStorageHandler.clear()`

Extends the default `window.localStorage.clear()` method returning the total of items cleared.

## TODO

* Implement the events handling via callback - see http://diveintohtml5.info/storage.html#storage-event
* Testing with all major browsers

## License

Creative Commons Attribution 3.0

# eStructures

Extended data structures for JavaScript.

## Available data structures

* [List](https://github.com/toystars/eStructures/blob/master/src/list.js)
* [Map](https://github.com/toystars/eStructures/blob/master/src/map.js)

## Usage
### * List
create an empty eList object
```javascript
var list = new eList();
```
add elements to eList
```javascript
list.add(5); // element is added to the end of list
list.add(1, 'eStructures'); // element is added to the specified index and other elements pushed further
list.add({name: 'library', valid: true});

// returns new list size when successful, -1 when error occurs
```

## Documentation
See the [Wiki](https://github.com/toystars/eStructures/wiki) for documentation.

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Contributions are **welcome** and will be fully **credited**.

We accept contributions via Pull Requests on [Github](https://github.com/toystars/eStructures).

### Setting up environment

Clone the repository and `cd` to project directory

Install all npm dependencies

```bash
$ npm install
```

Run gulp to watch on file changes (Including test files)
```bash
$ gulp
```


### Pull Requests

- **Add tests!** - Your patch won't be accepted if it doesn't have tests.

- **Document any change in behaviour** - Make sure the `README.md` and any other relevant documentation are kept up-to-date.

- **Consider our release cycle** - We try to follow [SemVer v2.0.0](http://semver.org/). Randomly breaking public APIs is not an option.

- **Create feature branches** - Don't ask us to pull from your master branch.

- **One pull request per feature** - If you want to do more than one thing, send multiple pull requests.

- **Send coherent history** - Make sure each individual commit in your pull request is meaningful. If you had to make multiple intermediate commits while developing, please [squash them](http://www.git-scm.com/book/en/v2/Git-Tools-Rewriting-History#Changing-Multiple-Commit-Messages) before submitting.


### Running Tests

``` bash
$ gulp test
```

## Issues

Check issues for current issues.

## Credits

- Mustapha Babatunde

## License

The MIT License (MIT). Please see [LICENSE](LICENSE.md) for more information.

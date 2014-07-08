# minstache

  Mini mustache template engine.

## Installation

    $ component install chemzqm/minstache

## Usage

* `{name}` no convert for single brackets.
* `{{name}}` for escape attribute.
* `{{!name}}` should not escape `name`.
* `{{#admin}}admin{{/admin}}` render admin if `admin`.
* `{{^authenticated}}login{{/authenticated}}` render login if not `authenticated`.
* `{{name.frist}}` render `first` attribute of `name`.
* `{{#contacts}}<li>{{name}}</li>{{/contacts}}` render `name`s of each contacts.

## API

### minstache(string, [obj])

  Compile and render the given mustache `string` with optional context `obj`.

### minstache.compile(string)

  Compile the mustache `string` to a stand-alone `Function` accepting a context `obj`.


## License

  MIT

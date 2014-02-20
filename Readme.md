*This repository is a mirror of the [component](http://component.io) module [yields/sidebar](http://github.com/yields/sidebar). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-sidebar`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# sidebar

  sidebar implementation, inspired by OSX notification center.

  _still very beta_

## Installation

    $ component install yields/sidebar

## API

### Sidebar(el, location)

Initialize new `Sidebar` with `element` and `location`.
location might be `top`, `bottom`, `left` or `right`.

### sidebar.open()

Open the sidebar.

### sidebar.close()

Close the sidebar.

### sidebar.toggle()

Toggle open / close

## License

  MIT

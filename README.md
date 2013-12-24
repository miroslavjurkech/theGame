# tty-solitaire
  ncurses-based klondike solitaire game.

![ttysolitaire gameplay](https://raw.github.com/mpereira/tty-solitaire/master/resources/ttysolitaire.gif)

## Dependencies
  - Terminal emulator with UTF-8 support
  - C library with multibyte locales support
  - Ncurses with wide-char/UTF-8 support

### Installing Ncurses

#### Ubuntu

    $ sudo apt-get install libncurses5-dev libncursesw5-dev

#### OS X

    $ sudo port install ncurses

## Compile
    $ git clone https://github.com/mpereira/tty-solitaire.git
    $ cd tty-solitaire
    $ make

## Install
    $ sudo make install

## Play
    $ ttysolitaire

## Usage
    usage: ttysolitaire [-v|--version] [-h|--help] [-p|--passes=NUMBER]
      -v, --version  Show version
      -h, --help     Show this message
      -p, --passes   Number of passes through the deck

## Running the unit tests
    $ make test

## Author
   [Murilo Pereira](http://murilopereira.com)

## License
   [MIT](http://opensource.org/licenses/MIT)

## Summary
`pbcopy` and `pbpaste` provide provide copying and pasting via the command line, similar to their 
[OS X counterparts][MANPAGE].

## Author
[Stuart Carnie](http://twitter.com/stuartcarnie)

## License
`pbcopy` and `pbpaste` are MIT licensed

## Help
`pbcopy`

  * copy contents of `STDIN` to clipboard

`pbpaste`

  * paste context of clipboard to `STDOUT`

## Usage
`pbpaste > .gitignore`  
  
  * Pastes the contents of the clipboard and outputs to a new file called `.gitignore`

`dir /s /r | pbcopy`

  * Copies the contents of the `dir /s /r` operation to the clipboard

[MANPAGE]: http://developer.apple.com/library/mac/#documentation/Darwin/Reference/ManPages/man1/pbcopy.1.html
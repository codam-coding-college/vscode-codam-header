<img
  src="https://raw.githubusercontent.com/oscarmulder/vscode-codam-header/master/codam.png" 
  width=128>

# Codam Header for VSCode
      
This extension provides the Codam header integration in VS Code. It's 42 original is found at https://github.com/kube/vscode-42header .

```bash
# ************************************************************************** #
#                                                                            #
#                                                        ::::::::            #
#   vscode-codam-header                                :+:    :+:            #
#                                                     +:+                    #
#   By: omulder <omulder@student.codam.nl>           +#+                     #
#                                                   +#+                      #
#   Created: 2019/01/11 19:08:02 by omulder        #+#    #+#                #
#   Updated: 2019/01/11 19:08:02 by omulder       ########   odam.nl         #
#                                                                            #
# ************************************************************************** #
```

## Install

Launch Quick Open with <kbd>⌘</kbd>+<kbd>P</kbd> and enter
```
ext install codamheader
```

## Usage

### Insert a header
 - **macOS** : <kbd>⌘</kbd> + <kbd>⌥</kbd> + <kbd>H</kbd>
 - **Linux** / **Windows** : <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>H</kbd>.

Header is automatically updated on save.


## Configuration

Default values for **username** and **email** are imported from environment variables.

To override these values, specify these properties in *User Settings* :

```ts
{
  "codamheader.username": string,
  "codamheader.email": string
}
```


## Issues

To report a bug or ask for a feature, please open a [Github issue](https://github.com/OscarMulder/vscode-codam-header/issues).


## License

MIT

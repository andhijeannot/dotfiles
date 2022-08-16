# Personal dotfiles

## Requirements

1. install [chezmoi][chezmoi]

2. initialize chezmoi with your dotfiles repo
  ```sh
  chezmoi init https://github.com/username/dotfiles.git  
  ```
3. Check what changes that chezmoi will make to your home directory by running:
  ```sh
  chezmoi diff
```
4. if you are happy with the changes that chezmoi will make then run:
  ```sh 
  chezmoi apply -v
  ```
5. On any machine, you can pull and apply the latest changes from your repo with:

```sh
chezmoi update -v
```















[chezmoi]: https://www.chezmoi.io/install/


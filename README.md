My Neovim config for [Astro Nvim](https://astronvim.github.io/)

Just put `init.lua` in:
```
/.config/nvim/lua/user
```

and then run:
```
nvim  --headless -c 'autocmd User PackerComplete quitall' -c 'PackerSync'
```
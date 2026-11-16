# nord.nvim

Personal port of the Nord theme for Neovim

## Installation

- lazy.nvim

  ```lua
  return {
      "xxyrnn/nord.nvim",
      lazy = false,
      priority = 1000,
      config = function()
          vim.cmd.colorscheme("nord")
      end
  }
  ```

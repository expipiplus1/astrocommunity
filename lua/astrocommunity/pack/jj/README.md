# Jujutsu/jj Pack

Pack for the [Jujutsu/jj](https://github.com/martinvonz/jj) Git-compatible VCS.

This plugin pack does the following:

- Adds jj tab to Neo-tree with [neo-tree-jj.nvim](https://github.com/Cretezy/neo-tree-jj.nvim)
- Adds Telescope pickers with [telescope-jj.nvim](https://github.com/zschreur/telescope-jj.nvim)
  - `<Leader>jf` for files in repository (falls back to git files if not in jj repo), like `jj files`
  - `<Leader>jd` for files with changes, like `jj diff`
  - `<Leader>jc` for files with conflicts, like `jj resolve --list`
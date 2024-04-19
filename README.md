# vscode-treemacs-theme
Visual Studio Code based icon theme for [Treemacs](https://github.com/Alexander-Miller/treemacs).

## Installation instructions using [Elpaca](https://github.com/progfolio/elpaca):
```elisp
  (use-package vscode-treemacs-theme
    :after treemacs
    :elpaca (:host github
             :repo "brunnseb/vscode-treemacs-theme"
             ;; need to include all the files, or the icons won't be visible
             :files ("*")))
```

## Installation instructions using [Straight.el](https://github.com/progfolio/straight.el):
```elisp
  (use-package vscode-treemacs-theme
    :after treemacs
    :straight (:host github
               :repo "brunnseb/vscode-treemacs-theme"
               ;; need to include all the files, or the icons won't be visible
               :files ("*")))
```

<div align="center">

# modern-icons-helm-rg.el

Modern icons for Emacs [helm-rg](https://github.com/cosmicexplorer/helm-rg).

</div>

This library integrates [modern-icons.el](https://github.com/taquangtrung/modern-icons.el) to modern and pretty SVG icons for [helm-rg](https://github.com/cosmicexplorer/helm-rg) search results in Emacs.

## Installation

Manually include [modern-icons-helm-rg.el](modern-icons-helm-rg.el) into your Emacs load path, or using [straight.el](https://github.com/radian-software/straight.el) like below:

  ```elisp
  (use-package modern-icons
    :straight (modern-icons :type git :host github
                            :repo "taquangtrung/modern-icons-helm-rg.el"))
  ```

## Usage

- Include the following code into your configuration file:

  ```elisp
  (require 'modern-icons-helm-rg)
  (modern-icons-helm-rg-enable)
  ```

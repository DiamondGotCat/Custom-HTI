# Custom-HTI
HTI index template

## How to use
To have the NIT installer find it, you need to clone this repository to your GitHub account and customize it.
Also, for custom HTI, you need to add an index before installing it.

Follow the steps below to set it up.
1. Fork this as name "Custom-HTI"
2. Turn on GitHub Pages
3. Add your work (packages.json)
4. Publish

## User
Now that your HTI repository is complete, we'll show you how to install your work. (This is an HTI salad system and allows installation from other repositories)
```
python nit.py install hti-salad
```
```
(#) install hti-salad
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  5627  100  5627    0     0  16707      0 --:--:-- --:--:-- --:--:-- 16697
Creator: <your-github-id>
mode(info|install|uninstall): <mode>
package-name: <your-package-id>
```
```
(+) Package 'hti-salad' installed.
```

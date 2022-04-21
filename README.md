# GLM-AED 
[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html)
[![Linux](https://svgshare.com/i/Zhy.svg)](https://svgshare.com/i/Zhy.svg)
[![macOS](https://svgshare.com/i/ZjP.svg)](https://svgshare.com/i/ZjP.svg)
[![Windows](https://svgshare.com/i/ZhY.svg)](https://svgshare.com/i/ZhY.svg)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AquaticEcoDynamics/glm-aed/HEAD?urlpath=rstudio)
[![Latest release](https://badgen.net/github/release/Naereen/Strapdown.js)](https://github.com/AquaticEcoDynamics/GLM_AED_test/releases)

## Cloning the repo with all submodule code

A basic clone will not include the code in the submodules so an extra argument is needed `--recurse-submodules`

### Cloning the latest code
```
git clone --recurse-submodules https://github.com/AquaticEcoDynamics/GLM_AED_test.git
```

### Cloning a particular tag
```
git clone --recurse-submodules -b testv1 https://github.com/AquaticEcoDynamics/GLM_AED_test.git 
```
## Updating existing submodules

```
git submodule update --remote
git add .
git commit -m 'updating submodule X and X'
git push
```

## Adding new submodules
```
git submodule add https://github.com/AquaticEcoDynamics/libaed2.git
```
where you replace the Github url with the url of the new module

## Archiving all code

Clone the repository as described above and zip entire repository.  The zip file can be uploaded to Zenado to get a DOI.  An automated intergration with Zenado will not archive the code from the submodules.

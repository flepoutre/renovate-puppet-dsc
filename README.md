# 33269

Reproduction for https://github.com/renovatebot/renovate/discussions/33269

## Current behavior

When we used DSC module in Puppetfile, for example (https://forge.puppet.com/modules/dsc/certificatedsc/5.1.0-0-9/readme) :

<code>
mod 'dsc-certificatedsc', '5.1.0-0-9'
</code>

"5.1.0-0-9" is not the latest version, so Renovate should open merge request with the latest release 6.0.0-0-0 but it doesn't.

## Expected behavior

Renovate seems to completely ignore dcs modules in Puppetfile for release check and we don't understand why. We have this problem only with dsc modules.

## Link to the Renovate issue or Discussion

Put your link to the Renovate issue or Discussion here : https://github.com/renovatebot/renovate/discussions/33269

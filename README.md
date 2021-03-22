<table style="width: 100%; border-style: none;"><tr>
<td width="140px" style="text-align: center;"><img src="android_default.png" style="max-width:100%" /></td>
<td><strong>Visual Studio Team Services Extension for Google Play</strong><br />
<i>Provides build/release tasks that enable performing continuous delivery to the Google Play store from an automated VSTS build or release definition</i><br />
<a href="https://marketplace.visualstudio.com/items?itemName=shbu.google-play-halt-rollout">Install now!</a>
</td>
</tr></table>

# Visual Studio Team Services Extension for Google Play: rollout user fraction update/halt release

This extension contains task for Google Play in-progress release rollout user fraction update. Support setting the user fraction as 0 to halt the rollout.

The extension leverage the code written in this one: [Visual Studio Team Services Extension for Google Play](https://marketplace.visualstudio.com/items?itemName=ms-vsclient.google-play)

## Prerequisites & Get started

Please follow the guide provided by [Visual Studio Team Services Extension for Google Play](https://marketplace.visualstudio.com/items?itemName=ms-vsclient.google-play)

The improvement here provided by this extension is that it supports the halting action by setting user fraction value as 0. This small tweak just brings us one huge step closer to a fully automated release flow.

## How to build this?

```
gulp
gulp create
```
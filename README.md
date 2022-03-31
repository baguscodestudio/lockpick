# Lockpick UI Minigame

![image](https://user-images.githubusercontent.com/60974759/161067952-d0acf8ef-ab1e-4540-bf83-b96268196b9c.png)

An easy lockpick export for FiveM.
I know this was in a lot of leaked resource and has been made similarly.
But this one I edited it myself from the codepen mentioned below.
Credits to [antoxa-kms](https://codepen.io/antoxa-kms/).

## Installation

1. Download the resource.
2. Drag and drop to resources folder.
3. Ensure or start the resource in server.cfg and you are done.

## Usage

Use `startLockpick` export to start lockpicking.

```lua
RegisterCommand('lockpicktry', function()
    local result = exports['lockpick']:startLockpick()
    print(result, 'lockpicking result')
end)
```

## Contribution

Suggestions and pull request are welcome!

## Acknowledgements

I do not take any credits from the UI code, credits to [antoxa-kms](https://codepen.io/antoxa-kms/pen/qbqoMy) codepen.

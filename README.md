# Mod Workspace

This repo is the workspace for a multi-mod development environment. It was based off the work that McJty did, original repo can be found here [https://github.com/McJtyMods/MultiWorkspace](https://github.com/McJtyMods/MultiWorkspace)

## Usage

1. Clone this repo
2. Symbolically link or 'git clone' mods into root directory
3. Open this project into IntelliJ, Eclipse or Visual Studio Code
4. Run `genIntellijRuns` from the `workspace` module

## Mods

The mods included in this workspace are

* [Dev World 2](https://github.com/FireBall1725/DevWorld2) - _Simple development world generator_
* [Mini Coal 2](https://github.com/FireBall1725/MiniCoal2) - _Don't waste fuel, creates mini coal and charcoal that smelt one item each_
* [Fire Library 2](https://github.com/FireBall1725/FireLib2) - _Library mod for my bigger mods_
* [Simply Grindstone](https://github.com/FireBall1725/SimplyGrindstone) - _Adds grindstones to the game, used to process ores_
* [Hue](https://github.com/FireBall1725/hue) - _A light mod, adding cool lighting features_

## Boilr Template

This repo also includes a boilr template to create new Minecraft Mod

### Installing boilr

`$ go get -u -v github.com/seanlatimer/boilr/...`

### Download the Minecraft Boilr template

`$ boilr template download fireball1725/ModWorkspace mod -f`

### Creating a new Minecraft mod using Boilr

`$ boilr template use mod path/to/new/mod`
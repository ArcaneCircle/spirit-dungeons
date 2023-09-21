# Spirit Dungeons

Incremental game with idle and offline progress!

**NOTE:** This is a port to WebXDC, the original game can be found [here](https://github.com/love-and-coffee/spirit-dungeons-legacy)

## Plot

**Necromancer** who has just lost the great war is ready to **rebuild his armies** and fight his way back to the top. In the process, he **finds his conscience** and is changing his way of life as a righteous necromancer together with his **willing dead**.

## Features

- 6 undead units;
- 10+ unique skills;
- 75+ trophies/achievements;
- Prestige mechanic;
- Idle and Offline progression;
- Premium theme using Web Monetization;

## Credits

- Cash, crowned skull, swords emblem, padlock, bookmarklet, trophy, haunting, grim reaper, evil bat icon by [Lorc](http://lorcblog.blogspot.com?ref=soul-not-found) under [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/);
- Yin yang, mummy head and vampire dracula icon by [Delapouite](http://delapouite.com?ref=soul-not-found) under [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/);
- Death skull icon by [sbed](https://opengameart.org/content/95-game-icons?ref=soul-not-found) under [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/);
- Thanks to [Decade Jam](https://discord.gg/Fq8wFgh) for helping me playtest the game;
- Thanks to Florent Cailhol and Randy Tayler for helping me compress the game to 13 kilobytes!

## Contributing

### Installing Dependencies

After cloning this repo, install dependecies:

```
pnpm i
```

### Checking the code format

```
pnpm check
```

### Testing the app in the browser

To test your work in your browser (with hot reloading!) while developing:

```
pnpm dev-mini
# Alternatively to test in a more advanced WebXDC emulator:
pnpm dev
```

### Building

To package the WebXDC file:

```
pnpm build
```

The resulting optimized `.xdc` file is saved in `dist-xdc/` folder.

### Releasing

To automatically build and create a new GitHub release with the `.xdc` file:

```
git tag v1.0.1
git push origin v1.0.1
```

# Mibew Emoji plugin

It replaces emojis codes with images in chat messages. The full list of supported emojis can be found at http://www.emoji-cheat-sheet.com/


## Installation

1. Get the archive with the plugin sources. At the moment the only option is to build the plugin from sources.
2. Untar/unzip the plugin's archive.
3. Create folder "`<Mibew root>`/plugins/Mibew/Mibew/Plugin/Emoji" (case does matter).
4. Put files of the plugins to the just created folder.
5. Add plugins definition to "plugins" structure in "`<Mibew root>`/configs/config.yml".
If the "plugins" stucture looks like `plugins: []` it will become:
```yaml
plugins:
    -
        name: "Mibew:Emoji"
```


## Build from sources

There are several actions one should do before use the latest version of the plugin from the repository:

1. Obtain a copy of the repository using `git clone`, download button, or another way.
2. Install [node.js](http://nodejs.org/) and [npm](https://www.npmjs.org/).
3. Install [Gulp](http://gulpjs.com/).
4. Install npm dependencies using `npm install`.
5. Run Gulp to build the sources using `gulp default`.

Finally `.tar.gz` and `.zip` archives of the ready-to-use Plugin will be available in `release` directory.


## License

[Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)

# Sublime-Text-3-Sync
A git repo for storing all my Sublime Text 3 configuration

# Installing
```bash
cd <ST3-Packages-Location>
rm -rf User
git clone git@github.com:Noah-Huppert/Sublime-Text-3-Sync.git User
```

`ST3-Packages-Location` is OS specific:
- Windows: `~/appdata/Sublime Text 3/Packages`
- OSX: `~/Library/Application Support/Sublime Text 3/Packages`
- Linux: `~/.config/sublime-text-3/Packages`

## Install package specific dependencies
**SublimeLinter-jshint**

```bash
npm install -g jshint
```

**SublimeLinter-ruby**

*You must have ruby installed*

**Gutter Color**

You must install ImageMagick.

On OSX you can use Homebrew:

```
brew install ImageMagick
```

On Linux you can install with `apt-get`:

```
sudo apt-get install ImageMagick -y
```
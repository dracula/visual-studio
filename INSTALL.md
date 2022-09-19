### [Visual Studio](https://www.visualstudio.com/)

#### Download from [Microsoft's official extension store](https://marketplace.visualstudio.com/items?itemName=dracula-theme.dracula)

> The most recommended way 🦇

In this option, you will always find the latest version of the theme for the newest version of Visual Studio.

- [Microsoft's official extension store](https://marketplace.visualstudio.com/items?itemName=dracula-theme.dracula)

Below you will see other download options, including different theme versions that support older versions of Visual Studio.

#### Downloading using Git

If you are a Git user, you can install the theme and keep up to date by cloning the repository:

```shell
git clone https://github.com/dracula/visual-studio
```

The default branch is the most recent year of Visual Studio (2022) we support. If you need to use an older version like 2019, you will need to check out that branch.

```shell
git checkout 2019
```

#### Downloading manually

You can download the theme [from GitHub](https://github.com/dracula/visual-studio/archive/2022.zip).

**Windows**

- Latest/2022: Download the theme [from GitHub (.zip)](https://github.com/dracula/visual-studio/archive/2022.zip) and unzip them.

- 2019/2017: Download the theme [from GitHub (.zip)](https://github.com/dracula/visual-studio/archive/2019.zip) and unzip them.
- 2015: Download the theme [from GitHub (.zip)](https://github.com/dracula/visual-studio/archive/2015.zip) and unzip them.
- 2012: Download the theme [from GitHub (.zip)](https://github.com/dracula/visual-studio/archive/2012.zip) and unzip them.

**Mac**

- Download the package [from GitHub (.zip)](https://github.com/dracula/visual-studio/archive/2019.zip) and unzip them.

#### How to install and activate the theme

**Windows**

1. Run the `DraculaTheme.vsix` file;
2. Select the Visual Studio version you want to install the theme and click `Install`;
3. With the installation complete, open your Visual Studio;
4. Navigate to `Tools` -> `Theme` and tick `Dracula Theme`;
5. Ready! 🚀

**Mac**

1. Start Visual Studio;
2. Go to `Preferences` -> `Text Editor` -> `Color Theme`;
3. Click "Add", find the unzipped folder and select the .vssettings file;
4. Click "Open";
5. Select the `Dracula Theme` theme option to preview it;
6. Click "Ok" to apply it;
7. Ready! 🚀

#### Known Issues

We know both C/C++ languages don't have the tokens to be coloured appropriately in the IDE. And they depend on packages and extensions in both VS and VSCode.

For context, this 🦇 Dracula Theme for VS uses the VSCode theme as a base.

Any suggestions and contributions are welcome. ✨

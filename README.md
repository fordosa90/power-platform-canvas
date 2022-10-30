# power-platform-canvas

Various Canvas apps and components to be reused for MSFT PowerPlatform development

# Table of Content

- [power-platform-canvas](#power-platform-canvas)
- [Table of Content](#table-of-content)
- [How-To](#how-to)
- [Details](#details)
  - [PixelDisplay](#pixeldisplay)

# How-To

The apps are stored as their unpacked version. To gain the usable *.msapp file, you will need to first pack them up. 

**The same applies when submitting a pull request with modifications, you will need to unpack the msapp file first.**

Official documentation: [PAC CLI](https://learn.microsoft.com/en-us/power-platform/developer/cli/reference/canvas#pac-canvas-unpack)

**Short summary**: after installing PAC CLI, run command `pac canvas unpack --msapp HelloWorld.msapp --source src` 

# Details

## PixelDisplay

A versatile reusable, resizable, responsive canvas component to show pixels on the screen based on input configuration.

More details: [LINK](PixelDisplay/README.md)
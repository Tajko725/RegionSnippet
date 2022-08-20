# RegionSnippet

## Summary

A simple snippet to quickly generate default regions, usually when I create WPF projects with MVVM I create default regions (regmax) in the ViewModel and for that I specifically create a text file in the project to not have to write the same thing many times. Now thanks to this extension I will shorten my writing a lot:)


This will save your time in creating regions.

![introduce movie](https://github.com/Tajko725/RegionSnippet/blob/master/RegionSnippet/Assets/Demo.gif)

## How to install

1. Download "RegionSnippet... .vsix" (Microsoft Visual Studio Extension) file from "Visual Studio Gallery" site.  
URL: https://marketplace.visualstudio.com/items?itemName=Tajko.RegionSnippet  or install from Extensions in Visual Studio
2. Open (double click on Explorer) the downloaded "RegionSnippet... .vsix" file.
3. Then, "VSIX Installer" was launched. Please click "Install".

## How to use

### Add maximum default regions (Properties, Commands, Constructors, Methods, Main, Events, Others)
- `regmax` [Tab]
Then, this snippet expanded following C# code.

```csharp
#region Properties

#endregion Properties

#region Commands

#endregion Commands

#region Constructors

#endregion Constructors

#region Methods
#region Main

#endregion Main
#endregion Methods

#region Events

#endregion Events

#region Others - enums etc.

#endregion Others - enums etc.

```
### Add half default regions (Properties, Constructors, Methods, Main)
- `regmid` [Tab]  

```csharp
#region Properties

#endregion Properties

#region Constructors

#endregion Constructors

#region Methods
#region Main

#endregion Main
#endregion Methods
```

### Add minimum default regions (Properties, Constructors, Methods)
- `regmin` [Tab]

```csharp
#region Properties

#endregion Properties

#region Constructors

#endregion Constructors

#region Methods

#endregion Methods
```


## Release Note

- v.1.0.0.0
  - First release, it contains `regmax, regmid, regmin` snippet.

## Support
If you would like to somehow repay me for my work in the form of ramen, for example, you can find more information here (PL): [SuppMe](http://kurso-center.pl/wsparcie/)

## License

[GNU GPL v.3](LICENSE.txt)

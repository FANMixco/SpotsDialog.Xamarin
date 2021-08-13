<a href="https://github.com/sponsors/FANMixco/" target="_blank">
   <img src="https://raw.githubusercontent.com/FANMixco/Xamarin-SearchBar/master/bmc-rezr5vpd.gif" alt="sponsor" />
</a>

## Get it

|  Package  |Latest Release|
|:----------|:------------:|
|**SpotsDialog.Xamarin**|[![NuGet Badge SpotsDialog.Xamarin](https://buildstats.info/nuget/SpotsDialog.Xamarin)](https://www.nuget.org/packages/SpotsDialog.Xamarin/)|


![alt text](https://camo.githubusercontent.com/d8108413298d70047f52cff9ac05603a5fd51988/687474703a2f2f332e62702e626c6f6773706f742e636f6d2f2d6c3155765657694d5341672f564c61355a6657346444492f41414141414141414e54632f7273576f755f71623042632f733332302f593648615453772e676966 "Preview")

**This is the latest library for Android:**

https://github.com/FANMixco/spots-dialog

Original Description:
Android AlertDialog with moving spots progress indicator packed as android library. Example:

## Usage
```C#
var progress = new SpotsDialog.Builder()
        .SetContext(this)
        .SetMessage(GetString(Resource.String.lblLoadingSecond))
        .Build();

progress.Show();
```

You can install the package from Nuget:

**PM> Install-Package SpotsDialog.Xamarin**

The original library was developed by:

[Maksym Dybarskyi](https://github.com/d-max)

https://github.com/d-max/spots-dialog

## License
[MIT](\LICENSE)

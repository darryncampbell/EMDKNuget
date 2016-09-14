# NuGet package for EMDK Xamarin Component
Nuget Package that wraps EMDK for Xamarin - Proof of concept

###This application is provided without guarantee or warranty

##Purpose


##Instructions

* https://www.nuget.org/
* https://dist.nuget.org/win-x86-commandline/latest/nuget.exe
* nuget pack Symbol.XamarinEMDK.nuspec
In Visual Studio
* Tools -> NuGet Package Manager --> Package Manager Settings.
* Select NuGet Package manager --> Package Sources
* Define a package source for the local nupkg file
OK out of that Window
* Tools --> NuGet Package manager --> Manager NuGet Packages for Solution
* Package source: [Whatever you defined in the previous step]


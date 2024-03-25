# Xamarin Avatar View (SfAvatarView)

The SfAvatarView control for Xamarin.Forms provides a graphical representation of user image that allows you to customize the view by adding image, background color, icon, text, etc.

For know more details about AvatarView:https://www.syncfusion.com/xamarin-ui-controls/xamarin-avatar-view

AvatarView user guide documentation:https://help.syncfusion.com/xamarin/avatar-view/getting-started

## Getting started with SfAvatarView
This section explains the steps required to work with the SfAvatarView control for Xamarin.Forms.

Adding SfAvatarView reference
You can add SfAvatarView reference using one of the following methods:

## Method 1: Adding SfAvatarView reference from nuget.org

Syncfusion Xamarin components are available in nuget.org. To add SfAvatarView to your project, open the NuGet package manager in Visual Studio, search for Syncfusion.Xamarin.Core, and then install it.

## Method 2: Adding SfAvatarView reference from toolbox

Syncfusion also provides Xamarin Toolbox. Using this toolbox, you can drag the SfAvatarView control to the XAML page. It will automatically install the required NuGet packages and add the namespace to the page. To install Syncfusion Xamarin Toolbox, refer to Toolbox.

## Method 3: Adding SfAvatarView assemblies manually from the installed location

If you prefer to manually reference the assemblies instead of referencing from NuGet, add the following assemblies in respective projects.

## Creating an SfAvatarView control
The SfAvatarView control is configured entirely in C# or in XAML. The following steps explain how to create an SfAvatarView control and configure its elements.

## Adding namespace for referred assemblies

**[XAML]**
```
xmlns:sfavatar="clr-namespace:Syncfusion.XForms.AvatarView;assembly=Syncfusion.Core.XForms"
```
## Adding the SfAvatarView control as the content of ContentPage
You can add a custom image for displaying in SfAvatarView using the ImageSource property.

**[XAML]**
```
<ContentPage.Content>
<Grid>
    <sfavatar:SfAvatarView ContentType="Custom"
                           ImageSource="alex.png"
                           VerticalOptions="Center"
                           HorizontalOptions="Center"   
                           HeightRequest="50"
                           CornerRadius="25"
                           WidthRequest="50" />
 </Grid>
</ContentPage.Content>
```
## How to run this application?

To run this application, you need to first clone the xamarin.forms-sfavatarview repository and then open it in Visual Studio 2022. Now, simply build and run your project to view the output.

## <a name="troubleshooting"></a>Troubleshooting ##
### Path too long exception
If you are facing path too long exception when building this example project, close Visual Studio and rename the repository to short and build the project.

## License

Syncfusion has no liability for any damage or consequence that may arise by using or viewing the samples. The samples are for demonstrative purposes, and if you choose to use or access the samples, you agree to not hold Syncfusion liable, in any form, for any damage that is related to use, for accessing, or viewing the samples. By accessing, viewing, or seeing the samples, you acknowledge and agree Syncfusion’s samples will not allow you seek injunctive relief in any form for any claim related to the sample. If you do not agree to this, do not view, access, utilize, or otherwise do anything with Syncfusion’s samples.
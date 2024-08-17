# Windows Customizations Guide

## Table of Contents
- [Using Windhawk](#using-windhawk)
- [Taskbar Mode Settings](#taskbar-mode-settings)

## Using Windhawk
- [Windhawk](https://windhawk.net/) provides advanced customization options for Windows.
- For more detailed taskbar customizations, visit [VinStart Theme's Windows 11 Taskbar Guide](https://www.vinstartheme.com/windows-11x-taskbar/).



## Taskbar Mode Settings
To customize the taskbar further, use the following settings:

```json
{
  "controlStyles[0].target": "Taskbar.TaskbarFrame#TaskbarFrame",
  "controlStyles[0].styles[0]": "Width=Auto",
  "controlStyles[1].target": "Taskbar.TaskbarFrame#TaskbarFrame > Grid#RootGrid",
  "controlStyles[1].styles[0]": "Background:=<AcrylicBrush TintColor=\"{ThemeResource SystemChromeAltHighColor}\" TintOpacity=\"0.5\" FallbackColor=\"{ThemeResource SystemChromeLowColor}\" />",
  "controlStyles[1].styles[1]": "Padding=0",
  "controlStyles[1].styles[2]": "CornerRadius=25,25,0,0",
  "controlStyles[1].styles[3]": "BorderThickness=0",
  "controlStyles[1].styles[4]": "BorderBrush:=<SolidColorBrush Color=\"{ThemeResource SurfaceStrokeColorDefault}\" />",
  "controlStyles[1].styles[5]": "Margin=5,0,5,0",
  "controlStyles[2].target": "Rectangle#BackgroundFill",
  "controlStyles[2].styles[0]": "Visibility=Visible",
  "controlStyles[3].target": "Rectangle#BackgroundStroke",
  "controlStyles[3].styles[0]": "Visibility=Collapsed",
  "controlStyles[4].target": "Taskbar.AugmentedEntryPointButton#AugmentedEntryPointButton > Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel",
  "controlStyles[4].styles[0]": "Margin=0",
  "controlStyles[5].target": "Grid#SystemTrayFrameGrid",
  "controlStyles[5].styles[0]": "Background:=<AcrylicBrush TintColor=\"{ThemeResource SystemChromeHighColor}\" TintOpacity=\"0.1\" FallbackColor=\"{ThemeResource SystemChromeLowColor}\" />",
  "controlStyles[5].styles[1]": "Margin=0,5,10,5",
  "controlStyles[5].styles[2]": "CornerRadius=20",
  "controlStyles[5].styles[3]": "Padding=5",
  "controlStyles[6].target": "SystemTray.ChevronIconView",
  "controlStyles[6].styles[0]": "Padding=0,-1",
  "controlStyles[6].styles[1]": "CornerRadius=20",
  "controlStyles[7].target": "SystemTray.NotifyIconView#NotifyItemIcon",
  "controlStyles[7].styles[0]": "Padding=0,-1",
  "controlStyles[7].styles[1]": "CornerRadius=20",
  "controlStyles[8].target": "SystemTray.OmniButton",
  "controlStyles[8].styles[0]": "Padding=0,-1",
  "controlStyles[8].styles[1]": "CornerRadius=20",
  "controlStyles[9].target": "SystemTray.CopilotIcon",
  "controlStyles[9].styles[0]": "Padding=0,-1",
  "controlStyles[9].styles[1]": "CornerRadius=20",
  "controlStyles[10].target": "SystemTray.OmniButton#NotificationCenterButton > Grid > ContentPresenter > ItemsPresenter > StackPanel > ContentPresenter > systemtray:IconView#SystemTrayIcon > Grid",
  "controlStyles[10].styles[0]": "Padding=4,0,4,0",
  "controlStyles[11].target": "SystemTray.IconView#SystemTrayIcon > Grid#ContainerGrid > ContentPresenter#ContentPresenter > Grid#ContentGrid > SystemTray.TextIconContent > Grid#ContainerGrid",
  "controlStyles[11].styles[0]": "Padding=0",
  "controlStyles[12].target": "SystemTray.StackListView#IconStack > ItemsPresenter > StackPanel > ContentPresenter > SystemTray.IconView#SystemTrayIcon",
  "controlStyles[12].styles[0]": "Padding=0",
  "controlStyles[13].target": "SystemTray.Stack#ShowDesktopStack",
  "controlStyles[13].styles[0]": "Margin=0,-4,-12,-4",
  "controlStyles[14].target": "SystemTray.OmniButton#NotificationCenterButton > Grid > ContentPresenter > ItemsPresenter > StackPanel > ContentPresenter > SystemTray.IconView#SystemTrayIcon > Grid > Grid > SystemTray.TextIconContent",
  "controlStyles[14].styles[0]": "Visibility=Collapsed",
  "controlStyles[15].target": "Taskbar.AugmentedEntryPointButton#AugmentedEntryPointButton > Taskbar.TaskListButtonPanel#ExperienceToggleButtonRootPanel > Border#BackgroundElement@CommonStates",
  "controlStyles[15].styles[0]": "Background:=<AcrylicBrush TintColor=\"{ThemeResource SystemChromeHighColor}\" TintOpacity=\"0.1\" FallbackColor=\"{ThemeResource SystemChromeLowColor}\" />",
  "controlStyles[15].styles[1]": "CornerRadius=20",
  "controlStyles[15].styles[2]": "Margin=-2,0,-10,0",
  "controlStyles[16].target": "Taskbar.TaskListButtonPanel@CommonStates > Border#BackgroundElement",
  "controlStyles[16].styles[0]": "CornerRadius=20",
  "controlStyles[17].target": "taskbar:TaskListLabeledButtonPanel@RunningIndicatorStates > Border",
  "controlStyles[17].styles[0]": "CornerRadius=20",
  "controlStyles[18].target": "Taskbar.TaskListLabeledButtonPanel@CommonStates > Rectangle#RunningIndicator",
  "controlStyles[18].styles[0]": "Width=6",
  "controlStyles[18].styles[1]": "Height=6",
  "controlStyles[18].styles[2]": "RadiusX=20",
  "controlStyles[18].styles[3]": "RadiusY=20"
}

---
-api-id: T:Microsoft.UI.Xaml.Input.XYFocusKeyboardNavigationMode
-api-type: winrt enum
---

<!-- Enumeration syntax.
public enum XYFocusKeyboardNavigationMode : int {
    Auto = 0
    Disabled = 2
    Enabled = 1
}
-->

# Microsoft.UI.Xaml.Input.XYFocusKeyboardNavigationMode

## -description
Specifies the 2D directional navigation behavior when using the keyboard arrow keys.

## -enum-fields

### -field Auto:0
Behavior is inherited from the elements ancestors. If all ancestors have a value of `Auto`, the fallback behavior is `Disabled`.

### -field Enabled:1
Arrow keys can be used for 2D directional navigation.

### -field Disabled:2
Arrow keys cannot be used for 2D directional navigation.

## -remarks
This enumeration is used by the [UIElement.XYFocusKeyboardNavigation](../microsoft.ui.xaml/uielement_xyfocuskeyboardnavigation.md) property.

2D directional navigation is used to navigate a user interface (UI) with an Xbox controller or keyboard directional arrows. For more info, see [Gamepad and remote control interactions](/windows/apps/design/input/gamepad-and-remote-interactions) and [UIElement.XYFocusKeyboardNavigation](../microsoft.ui.xaml/uielement_xyfocuskeyboardnavigation.md).

## -see-also

## -examples


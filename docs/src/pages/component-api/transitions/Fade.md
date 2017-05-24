# Fade



## Props
| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| in | boolean | false | If `true`, the component will transition in. |
| enterTransitionDuration | number | duration.enteringScreen | Duration of the animation when the element is entering. |
| leaveTransitionDuration | number | duration.leavingScreen | Duration of the animation when the element is exiting. |
| children | Element |  |  |
| onEnter | Function |  | Callback fired before the component enters. |
| onEntering | Function |  | Callback fired when the component is entering. |
| onEntered | Function |  | Callback fired when the component has entered. |
| onExit | Function |  | Callback fired before the component exits. |
| onExiting | Function |  | Callback fired when the component is exiting. |
| onExited | Function |  | Callback fired when the component has exited. |

Any other properties supplied will be spread to the root element.
## Classes

You can overrides all the class names injected by Material-UI thanks to the `classes` property.
This property accepts the following keys:


Have a look at [overriding with class names](/customization/overrides#overriding-with-class-names)
section for more detail.

If using the `overrides` key of the theme as documented
[here](/customization/themes#customizing-all-instances-of-a-component-type),
you need to use the following style sheet name: `null`.
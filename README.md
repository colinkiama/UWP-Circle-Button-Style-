# UWP-Circle-Button-Style-
A perfect circlular button which has a round highlight while hovering over it too. Posted here because there was no help for this on the internet.

![Image Preview](circleButtonGIF.gif "Preview")

Go ahead and fork, make it your own :)

<h2>How to use this style</h2>

You can either add the style in between resources tags like this: 
``` XAML
<Grid.Resources> <!-- Put Style Here -->  </Grid.Resources> 
```

Or you can add it directly into the Style tags of a button (In order for this to work, you need to remove the x:Key attribute) :
``` xaml
 <Button>
  <Button.Style>
   <!-- Put Style Here --> 
  </Button.Style>
 </Button>
 ```
 
 <b>Note</b>: Whenever you see `<!-- Put Style Here -->`, literally copy and paste the style from the xaml file in that position.

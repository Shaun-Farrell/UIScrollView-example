# Simple UIScrollView example in interface builder (Storyboard)

## Description
This is a simple example of a UIScrollView set up in interface builder.  
This can be challenging, the objectives of this example are to have a scrollview that:

* Uses the latest safe area layouts
* Scrolls content if the content view length exceeds the screen height
* Does not scroll if the content view length is less than the screen height
* Handles rotation

## Usage
If you run this in a iPhone 6 portrait it will not scroll.  
If you run this in a iPhone 6 landscape it will scroll.

## Key points
Scrollview (inside the main view) is set up to have a content view.  
The content view has equal height and width to the main view.  
Lower priority (250) is given to the equal height constraint (allowing it to be broken)
Content inside the content view must touch each edge of the content view.
Lower priority (250) constraints can be given to those less important such as trailing and leading constraints.

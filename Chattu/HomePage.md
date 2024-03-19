#AppLayout
- The wrapped component receives all the props of the container, along with a new prop, data , which it uses to render its output.
- Inside the AppLayout we make Title and Some Grids
- Title component will be made separately inside the shared folder of componenents as it can be accessed by every page

#Header
- Header(navbar) is completed using various functionalities of mui such as box, tooltip, typography, etc.
- major role is played by flexGrow property of boxes which shift an entire available space

#Grid
- Grid is a part of MUI components in which we get to divide a page into 12 grids(just like vanilla CSS)
- we leave 4rem in the upper side for header as header gets to stay for different screen sizes.
- we add styles on grid using sx={{}}

#Box 
- box is also a MUI component used to make things like containers.
- sx={{flexGrow:1}} gives all the space to the current box that is available

#Tooltip
- this is used to label an existing button or even text with arrows, different colors, different direction of labelling, etc

#useState
- we use use state to implement buttons like search, notification, manage group

#Suspense
- using suspense shows ...Loading until the website gets loaded. this is useful for heavy websites.

#LayoutLoader
- Uses skeleton(from MUI) to show a basic skeleton of what the website is about to be while loading

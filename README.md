# Storyboard-Tips
Shortcut tips to manage storyboard easily.


# cmd 
when draging view in sotoryboard by pressing cmd it will only place under the main view. 

# cmd = 
by pressing cmd and = (equal) while a label is selected, the label will automicaly resize with its text size.  

# Autoresizing 
we can find this under left menu clicking size inspector . By using this we can easily make auto resizing for any view we. there are 6 selection option in autoresizing . Left, top, right, bottom selection and horizontal and vertical selection. by seltecting left ,top right bottom we can place it posiiton to view and by selection horizontal or vertical line we ca make the view size autoresizing according device size. 

# Duplicating Objects
We can simply duplicate any object by copy(cmd + c) and and paste(cmd + v) . But we can do it better way, by holding option key and then drag the object you want to duplicate to the position you want. By holding option key we can do both duplicate and positioning at the same time. 

# Updating Constraints 
We can update constraints in 3 way after setting them. After chnage object position in view: 
    1.  go to the left side menu selecting size inspector and changing contraints value. 
    2.  selecting Update Constraint Constants from bottom menu Resolve Auto layout isues. 
    3.  Double clicking constraint form view and change the value.
    
# Orphaned Outlets and Actions 
Sometimes we creates outlets or action in view controller and remove that outlet or action from view controller without removing the reference from the view.  And then if we run our code then we will get NSUnknownKeyException. Easy way to do this is Right click in your viewcontroller in story board (top yellow button) and look for the yellow warning button and remove it. 

# Formatting Code
Select area you want to formate then hit controll + I . Or hit cmd + A to select all and then hit control + I.

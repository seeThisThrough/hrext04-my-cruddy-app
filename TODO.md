# MVP
- [√] store items
 - [√] create new item
 - [√] select item
 - [√] edit/update item
 - [√] delete item


 # Detail Todo
 - [ ] Front End
   - [√] display items
   - [√] enter new item
   - [√] select item for edit
   - [√] select item for delete
   - [√] a form!

   - [ ] UI/UX
     - [ ] Confirmation of delete/update
     - [ ] Sortable list
     - [ ] Navigation/Pagination
     - [ ] Mouse over Preview
     - [ ] Searching/Filtering
     - [ ] Animations/Transitions

  - [ ] Library Considerations
    - [ ] underscore
    - [√] jquery
    - [ ] moment.js
    - [ ] c3.js (charts.js)

 ## Next Steps

  - [ ] factor out common functionality
  - [ ] testing


  ## Feature list
  * denotes on my to do for the project
  2.5 days = 20 hours

  ### difficulty scale 1-10. 1 meaning it's already finished 10 meaning what?!?!

  5 = 3 hours
  7 = 5 hours
  10 = full day + ??
  


  Basic Plan
    To make use of a blog/vlog type template to use during my immersive. I love keeping a liveJournal but using websites are kinda lame since I have to have online access and log in and stuff. It'd be cool to make my own blog site which I can work on in my freetime and hopefully make into a real website towards the end of my immersive!
    



  HIGH Priority *** MVP ***
    Every journal site implements our starting site's functionality. I need to work on changing the add text button to display my posts to the page. Delete/Edit buttons to change and delete older entries. I'd like to know what day/time I posted my entries so implementing moment.js or timeago.js would be useful for displaying those times in a friendly way.

         Workload
          *(7)ability to select and delete multiple items (checkbox?)
           -maybe implement a check box which will select the key-value object and either delete or sort the list according to the parameters chosen

          *(3)time stamps (moment.js)
           -simply display the time post was made in a relative fashion that's eye       pleasing (using moment.js on timestamp, css to put time in the corner)

    Photos are pictures a big part of how I see the world, so being able to upload and insert from other URLs or my own workspace would be idea. I think this could either be done by using an upload button, or implementing HTML/CSS In the actual post

         Workload
           *(5)upload files/images
           -figure out an upload button for img files. when uploaded, put the        photos into the text field or as its own object

  MEDIUM priority *** BONUS FEATURES ***
    A share button would be cool, To be able to share my blog with others and to get traffic to my site. A space for people to comment on my posts in a way that doesn't take away from the feel of the site would be cool
          Workload
            *(7)pagination (if more than 10 show a next button)
            *(5)drag and drop to arrange

  LOW priority     *** STUFF TO SHOW OFF ***
    having other users would be cool as well; no project is fun by yourself; but obviously this page is just for me so I'm not too worried in implementing this functionality.  
    
          Workload
             *(5)share item
              -a button which allows user to send a hyperlink to the current       content
             *(5)delete item confirmation
              -use alert box to see if user really wants to delete certain items
             *(3)Panic Button
              -hmm something that just runs animate dropdown on all elements
              (1)secret corgi
              -secret corgi? as in a corgi embedded on the page already hidden?       and then shown when clicked?


<!--   add due date
  
    -simply display the time post was made in a relative fashion that's eye pleasing (using moment.js on timestamp, css to put time in the corner)
  *(5) format the display of the items in a list (need to add more detail)
    -css heavy to make the font/text box pretty (last implementation)
  *(5) color coded priority
  *(4)  highlight certain items
    -cool idea to use Jscript to make every other post a different color
  
  -if your list gets to more than 10 items; have seperate items append to a new page
  category pages (not really pages, just a show/hide trick)
  strike-through completed/deleted items (styling)
  add more items button, that shows another input section allowing for multiple items to be added at once
  Fun stuff
  auto-complete when searching/filtering
  (??) fix the layout
  mouse over to see details
  add status/priorty and allow for sorting based on status/priority
  
  search/filter on keyup/keydown
  reminders? (push operation?)
  
  fillet edges of boxes
  font changes/choices? (google fonts)
  Highlight based on status/priority/due date
  options page (ability to set/toggle options)
  show deleted items and allow for undelete

 -->

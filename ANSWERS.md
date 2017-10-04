## Questions

What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?




Go to `localhost:3000/teachers` in your browser; why does this not work?

This doesn't work because there isn't a GET route for teachers 


What type of request did your browser just perform?

A GET request 


Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?

localhost:3000/teachers


Why does `localhost:3000/teachers` work now?

It works because it has params to send now 

It works now because a POST request to /teachers maps to teachers#create, which renders show.html.erb
A drop-in profiles system for Meteor.js

@@TODO:

Adding the module to your project will do the following:

* Create profile routes
  - /profile/:username      :: view the profile for that user
  - /profile/:username/edit :: create or edit a profile for that user

A user can only edit their own profile.  Anyone aside from `joebloggs`
who hits `/profile/joebloggs/edit` will be redirected to
`/profile/joebloggs`

* Create a client/profile.html template
* Create a profile_fields.js file where you can define the fields you want

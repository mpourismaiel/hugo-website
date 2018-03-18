+++
fragment = "contact"
#disabled = true
date = "2017-09-10"
lastmod = "2017-09-10"
weight = 1100
#background = "light"
selfLink = "contact-fragment"
form_name = "defaultContact"

title = "Contact fragment"
subtitle  = "*not working on demo page*"

# PostURL can be used with backends such as mailout from caddy
posturl = "https://api.formbucket.com/f/buk_erxTDecOse8T6NbO5JOx6wgz"
email = "mpourismaiel@gmail.com"
button = "Send Button" # defaults to theme default
netlify = true

[message]
  success = "Thank you for awesomely contacting us." # defaults to theme default
  error = "Message could not be send. Please contact us at mail@example.com instead." # defaults to theme default

# Only defined fields are shown in contact form
[fields.name]
  text = "Your Name *"
  error = "Please enter your name" # defaults to theme default

[fields.email]
  text = "Your Email *"
  error = "Please enter your email address" # defaults to theme default

[fields.phone]
  text = "Your Phone *"
  error = "Please enter your phone number" # defaults to theme default

[fields.message]
  text = "Your Message *"
  error = "Please enter a message" # defaults to theme default

# Optional hidden form fields
# Fields "page" and "site" will be autofilled
[[fields.hidden]]
  name = "page"

[[fields.hidden]]
  name = "someID"
  value = "example.com"
+++

+++
fragment = "table"
#disabled = false
date = "2017-10-10"
lastmod = "2017-10-10"
weight = 500
background = "light"
self_link = "table-fragment"

title = "Table Fragment"
subtitle= "Tables are responsive by default"

[header]
  [[header.values]]
    text = "Header 1"
    # hide_on_mobile = true

  [[header.values]]
    text = "Header 2"

  [[header.values]]
    text = "Header 3"
    hide_on_mobile = true

  [[header.values]]
    text = "Header 4"
    hide_on_mobile = true

  [[header.values]]
    text = "Header 5"

  [[header.values]]
    text = "Header 6"

[[rows]]
  [[rows.values]]
    header = "Row 1"

  [[rows.values]]
    text = "Value"

  [[rows.values]]
    text = "Long Value"

  [[rows.values]]
    text = "Value"

  [[rows.values]]
    button = "Long Button"
    link = "#"
    color = "success"

  [[rows.values]]
    button = "Button"
    link = "#"
    color = "danger"
    center = true

[[rows]]
  [[rows.values]]
    header = "Row 2"

  [[rows.values]]
    text = "Value"

  [[rows.values]]
    text = "Value"

  [[rows.values]]
    text = "Long Value"

  [[rows.values]]
    text = ""

  [[rows.values]]
    icon = "fa-download"
    link = "#"
    center = true
+++

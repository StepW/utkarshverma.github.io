+++
widget = "portfolio"
headless = true
active = true
weight = 65

title = "Projects"
subtitle = ""

[content]
  page_type = "project"
  filter_default = 0
  
  [[content.filter_button]]
    name = "All"
    tag = "*"
  
  [[content.filter_button]]
    name = "Electronics"
    tag = "electronics"
  
  [[content.filter_button]]
    name = "Programming"
    tag = "programming"

[design]
  columns = "3"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

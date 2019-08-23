+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"
headless = true
active = true
weight = 1

title = "Projects"
subtitle = ""

[content]
  page_type = "project"
  filter_default = 0
  
  [[content.filter_button]]
    name = "All"
    tag = "*"
  
  [[content.filter_button]]
    name = "Penn Labs"
    tag = "Penn Labs"
  
  [[content.filter_button]]
    name = "Python"
    tag = "python"

  [[content.filter_button]]
    name = "Docker"
    tag = "docker"

[design]
  columns = "1"
  view = 3
+++


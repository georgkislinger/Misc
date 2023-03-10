# Misc
batch crop cmd line irfanview
navigate to irfanview installation folder (likely C:\Program Files\Irfanview)

> i_view64.exe "D:\input-location\*.tif" /crop=(1024,0,39936,20189) /convert="D:\output-location\*.tif"

input can equal output
numbers for crop=(starting_point_x,starting_point_y,resulting_size_x,resulting_size_y)

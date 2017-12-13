# Study-break-alarm-Python

import time
import webbrowser

break_first = 1

total_breaks = 3

count = 1

print ("This break counter started " + time.ctime())
while (break_first <= total_breaks):
  
 
  print ("Nice work! You are on your break number:") 
  print count 
  count = count + 1

    
  time.sleep(60*60)
  webbrowser.open ("https://www.youtube.com/watch?v=d3UwMNdriEshttps://www.youtube.com/watch?v=d3UwMNdriEs")
  break_first = break_first + 1
  

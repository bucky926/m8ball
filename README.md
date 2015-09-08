# m8ball

def p1():
  f="C:\\Users\PC12\Desktop\8ball.jpg"
  p=makePicture(f)
  s=makeStyle(sansSerif,bold,18)
  addTextWithStyle(p,75,75,"Without",s,white)
  addTextWithStyle(p,75,100,"a doubt",s,white)
  repaint(p)
 

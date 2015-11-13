
 
//Spring2D s1, s2;

float gravity = 9.0;
float mass = 2.0;

int angle = 0;
void setup() {
  size(180, 180);
  stroke(0);
 
  
  fill(255, 126)
void draw () 
  background(255, 64, 0);
  line(80,0, mouseX, mouseY);
 if (mousePressed == true) {
    angle += 1;
   float val = cos(radians(angle)) * 12.0;
 for (int a = 0; a < 360; a += 5) {
  float xoff = cos(radians(a)) * val;
      float yoff = sin(radians(a)) * val;
      fill(175);
      stroke(14,35,355);
      ellipse(mouseX + xoff, mouseY + yoff, val, val);
 fill(250);
 stroke(95,174,9);
    ellipse(mouseX, mouseY, 75, 2);
    
  
  } 
}
 }                                   

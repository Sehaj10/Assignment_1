void setup() 
{
  size(1200, 800); 
  frameRate(2);
}

void draw() 
{
  int pos= 100; // Distance btw each ellipse
  float d = dist(0, 0, width, height); //Maximum Canvas Size
  float s= 200; //Size of ellipse
  background(0);
  strokeWeight(random(1,10));
  circle(width/2, height/2, 8);
  //Setting up the grid
  for(int i = 0; i <= width; i += pos)
  {
    for(int j = 0; j <= height; j += pos)
    {
      float size = dist(width/2, height/2, i, j); //Dist from the center of the grid
      size = (size/d)*s;
      ellipse(i, j, size, size);
      stroke(random(0,255), random(0,255), random(0,255));
      noFill();
    }
  }
  saveFrame("DATT_Assignment_1.png");
}

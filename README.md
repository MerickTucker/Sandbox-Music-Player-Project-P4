@@ -6,8 +6,14 @@ import ddf.minim.spi.*;
import ddf.minim.ugens.*;
//
//Global Variables
Minim minim;
AudioPlayer song;
//
void setup() {} //End setup
void setup() {
  minim = new Minim(this);
  song = minim.loadFile("../Music/groove.mp3");
  song.loop(0);
} //End setup
//
void draw() {} //End draw
//

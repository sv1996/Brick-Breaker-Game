# Brick-Breaker-Game

## This is famous brick Breaker Game developed in Core Java and Swing GUI Toolkit.

# Starting code 

```

package brickBracker;

import javax.swing.JFrame;

public class MainGame {

	public static void main(String[] args) {
		JFrame obj = new JFrame();
		obj.setBounds(10, 10, 700, 600);
		obj.setTitle("BREAKOUT BALL");
		obj.setResizable(false);
		obj.setVisible(true);
		obj.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		GamePlay gameplay=new GamePlay();
		obj.add(gameplay);

	}

}
```

# How to Play This Game 

1. open all source code in Eclipse IDE 
2. Run MainGame.java file as main file
3. after that whole game window will open and you see a ball with bricks 
4. press Enter key to start the game.
5. When ball hits the brick it starts loosing its dimension and score added to the player account.
6. you can slide left or right of piller to accces the ball.










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






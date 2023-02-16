# How To Catch A Cheater With Math

We would like to catch cheaters who are using trick coins that come up heads more than half the time.

- Primer. How To Catch A Cheater With Math [YouTube channel]. From: https://youtu.be/XTcP4oo4JI4

### How to use
![Screenshot 2023-02-16 at 13-06-11 jogobeny_how-to-catch-a-cheater-with-math](https://user-images.githubusercontent.com/79165095/219360550-804e36b4-5eac-4494-b255-7e62612c801b.png)

#### What is Threshold
Threshold value is a limit for a player to be not accused of cheating.
```python
possible_cheaters = [p for p in players if p.heads >= THRESHOLD]
```

Accuse all players of cheating             |  Suboptimal accusing
:-------------------------:|:-------------------------:
![Screenshot 2023-02-16 at 12-46-54 main - Jupyter Notebook](https://user-images.githubusercontent.com/79165095/219359584-83f98639-aa97-47ad-9987-5d93ea7a852d.png)  |  ![Screenshot 2023-02-16 at 12-47-02 main - Jupyter Notebook](https://user-images.githubusercontent.com/79165095/219359594-858391c1-ba61-4ace-92b0-1484e613b5d1.png)

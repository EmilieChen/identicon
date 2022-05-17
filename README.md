# Identicon

**TODO: Add description**

## Presentation

  The Identicons generated are used as Github default avatar. Here are some examples :


  ![alt text](https://github.com/EmilieChen/identicon/tree/main/identicons_examples/star.png)
  \newline
  iex> Identicon.main ("star")

  ![alt text](https://github.com/EmilieChen/identicon/tree/main/identicons_examples/wood.png)
  \newline
  iex> Identicon.main ("wood")

  ![alt text](https://github.com/EmilieChen/identicon/tree/main/identicons_examples/moon.png)
  \newline
  iex> Identicon.main ("moon")

  ![alt text](https://github.com/EmilieChen/identicon/tree/main/identicons_examples/sun.png)
  iex> Identicon.main ("sun")

  ![alt text](https://github.com/EmilieChen/identicon/tree/main/identicons_examples/river.png)
  iex> Identicon.main ("river")

  ![alt text](https://github.com/EmilieChen/identicon/tree/main/identicons_examples/banana.png)
  iex> Identicon.main ("banana")

  Our Identicons are 5×5 sprites of 50 pixels. They are generated using a hash of the input string as the seed. The algorithm walks through the hash and colors sprites depending on even or odd values of the hash. The colors is determined by the first three values of the hash. The algorithm ensures a huge number of unique 250 x 250 resolutions identicons.


## Reference
  This project is realised by following a course on the Udemy platform. Here is the link : https://www.udemy.com/share/101Wui3@-veyc42ZxoO0C8AGRhvg96PeMCqt8vJ49HkThn9JELvy9S8tqU0FeDkqcTBfGDGHMg==/



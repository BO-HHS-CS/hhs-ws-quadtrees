# HHS CS Workshop: Quadtrees
Using quadtrees to make art.  
Inspired by [Michael Fogleman's](https://www.michaelfogleman.com/) cool [repo](https://github.com/fogleman/Quads) on quadtrees.  
A target image is given. A quadtree parent is initialized as one rectangle with the average color of the target image. Every iteration, a quadtree is selected to be split into 4 children quadrants, each consisting of the average color within that quadrant. The quadtree to split is determined by which split reduces the error of the rendered image with the target image the most. 
## Quadtree Object
Contains:
- Rectangle bounds within the image.
- Rendered image within that quadrant and its average color.
- Error within said quadtree with target image and how much error could be reduced if split.
- 4 children quadtrees.
## Examples:
### Frieren:
**Quadtree Rendering:**  
![Rendered Gif: Frieren](gifs/frieren.gif)
<details>
  <summary>Target Image (Click to Expand)</summary>

![Target Image: Frieren](images/fr.jpg)
</details>

### Alpaca:
**Quadtree Rendering:**  
![Rendered Gif: Alpaca](gifs/alpaca.gif)
<details>
  <summary>Target Image (Click to Expand)</summary>

![Target Image: Alpaca](images/alpaca.jpg)
</details>

### Gates and Hillman Centers:
**Quadtree Rendering:**  
![Rendered Gif: Gates and Hillman](gifs/Gates&Hillman.gif)
<details>
  <summary>Target Image (Click to Expand)</summary>

![Target Image: Gates and Hillman](images/gateshillman.jpeg)
</details>

### Obama:
**Quadtree Rendering:**  
![Rendered Gif: Obama](gifs/obama.gif)
<details>
  <summary>Target Image (Click to Expand)</summary>

![Target Image: Obama](images/obama.jpg)
</details>

### Mr. Shelby:
**Quadtree Rendering:**  
![Rendered Gif: Shelby](gifs/shelby.gif)
<details>
  <summary>Target Image (Click to Expand)</summary>

![Target Image: Shelby](images/shelby.jpg)
</details>

### Zebra:
**Quadtree Rendering:**  
![Rendered Gif: Zebra](gifs/zebra.gif)
<details>
  <summary>Target Image (Click to Expand)</summary>

![Target Image: Zebra](images/zebra.jpg)
</details>

### XKCD Comic #1683:
**Quadtree Rendering:**  
![Rendered Gif: XKCD](gifs/xkcd.gif)
<details>
  <summary>Target Image (Click to Expand)</summary>

![Target Image: XKCD](images/xkcd.png)
</details>



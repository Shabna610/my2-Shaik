# Shabna Shaik
### Favorite Vacation Spot

**Nandi Hills** holds a special place in my heart as my favorite vacation spot. The tranquility of the lush surroundings, coupled with the breathtaking sunrise views, makes it a haven for rejuvenation. The cool breeze that gently sweeps over the hills and the lush greenery create an atmosphere of serenity that is hard to find elsewhere. Every visit to Nandi Hills feels like a soulful escape from the hustle and bustle of the city, allowing me to reconnect with nature and find inner peace.

**It's more than just a spot for me; it's a retreat from the bustling city life.** It's a place where I can pause, breathe, and find solace in the simplicity of nature. Every time I leave, I carry a piece of its tranquility with me, reminding me that there's always a peaceful haven waiting atop those misty hills.

------------------------------------------------------------------

## Activities at My Favorite Vacation Spot

1. ***Hiking***: Enjoy scenic treks with stunning views.
2. ***Sunrise Watching***: Witness breathtaking sunrises.
3. ***Paragliding***: Embrace the freedom of gliding high where the sky is our playground.
- **Favorite foods at my Favorite Vacation Spot**
    - ***Corn:*** Savoring the delicious roasted corn while taking in the breathtaking views at Nandi Hills is a delightful experience.

    - ***Tea:*** Enjoying a hot cup of aromatic tea amidst the serene surroundings of Nandi Hills enhances the overall experience and adds to the enjoyment.

[Know me more](MyStats.md)

------------------------------------------------------------
## Stay Active with These Choices

Searching for exciting ways to keep fit and active? Look no further! Below, you'll find a selection of sports I enjoy, each with its unique reasons for recommendation, along with the weekly hours to invest in these activities.

| Sport Name       | Reason for Recommendation             | Hours per Week |
|------------------|---------------------------------------|----------------|
| Tennis           | Great for improving agility and focus | 4              |
| Hiking           | A fantastic way to connect with nature| 6              |
| Swimming         | Excellent full-body workout           | 5              |
| Cycling          | Eco-friendly and fun transportation   | 3              |

--------------------------------------------------------------
## Pithy Quotes by Scientists

> "Science is the great adventure of our time." - Carl Sagan

> "The only source of knowledge is experience." - Albert Einstein

## Code Snippet and Stack Overflow with Q & A

> [*Stack Overflow Question*](https://stackoverflow.com/search?q=Placing+Items+on+a+Circle+)
> 
> Placing Items on a Circle.

```
@mixin on-circle($item-count, $circle-size, $item-size) {
  position: relative;
  width:  $circle-size;
  height: $circle-size;
  padding: 0;
  border-radius: 50%; 
  list-style: none;       
  
  > * {
    display: block;
    position: absolute;
    top:  50%; 
    left: 50%;
    width:  $item-size;
    height: $item-size;
    margin: -($item-size / 2);
  
    $angle: (360 / $item-count);
    $rot: 0;

    @for $i from 1 through $item-count {
      &:nth-of-type(#{$i}) {
        transform: 
          rotate($rot * 1deg) 
          translate($circle-size / 2) 
          rotate($rot * -1deg);
      }

      $rot: $rot + $angle;
    }
```

[Source: CSS Tricks for Styling Buttons](https://css-tricks.com/snippets/sass/placing-items-circle/)
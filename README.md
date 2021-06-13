# Breaking Bad Project

This project gives information about all the characters in one of my favourite Web-Series "The Breaking Bad" and displays information about each character in a flip-card.

Also it filters the characters as we search for particular ones

# Live Link

[Breaking Bad Live🚀](https://saikatxshrey.github.io/breaking-bad-project/)

# Demo
Project Video

https://user-images.githubusercontent.com/76695320/118493258-8a3c6000-b73e-11eb-97b3-82d654e1e1b6.mp4

# Screenshot
![](image/Screenshot%20(982).png)

## API Reference

Api used is [Breaking Bad Api](https://breakingbadapi.com/documentation)

#### Get characters

```http
  GET /api/characters

  https://www.breakingbadapi.com/api/characters?name=${query}
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `search_query` | `string` | **Required**. Your Search  |
  
## Deployment

To deploy this project run

```bash
  npm run deploy
```

  
## Lessons Learned

This project is made using functional component and Hooks is used heavily in this project. Particularly useState and useEffect and axios module(fetch from api) and also working with api becomes more handy by making this project

And the api request sent makes a little bit of time to respond so i made sure to use a loader...and making a animated loader screen manually is tough so i faced some difficulty there.

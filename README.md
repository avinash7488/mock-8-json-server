## Deploy JSON Server to Vercel

A template to deploy [JSON Server](https://github.com/typicode/json-server) to [Vercel](https://vercel.com), allow you to run fake REST API online!

Demo from this repository: 

1. https://mock-8-json-server-tau.vercel.app/
2. https://mock-8-json-server-tau.vercel.app/users
3. https://mock-8-json-server-tau.vercel.app/movies

### How to use

1. Click "**Use this template**" or clone this repository.
2. Update or use the default [`db.json`](./db.json) in the repository.
3. Sign Up or login into [Vercel](https://vercel.com).
4. From the Vercel dashboard, click "**+ New Project**" then "**Import**" your repository.
5. In the "**Configure Project**" screen, leave everything default and click "**Deploy**".
6. Wait until deployment is done, and your own JSON server is ready to serve!

## Default `db.json`

```json
{
  "users": [],
  "movies": [
    {
		"id" : 1,
		"poster" : "https://image.tmdb.org/t/p/original/9Gtg2DzBhmYamXBS1hKAhiwbBKS.jpg",
		"title" : "Doctor Strange in the Multiverse of Madness",
		"director" : "Sam Raimi",
		"year" : 2022,
		"genre" : "Action",
		"IMDB_Rating" : 6.8,
		"ticket" : 200
	},
	{
		"id" : 2,
		"poster" : "https://images2.9c9media.com/image_asset/2019_2_14_f02ce589-7434-4ef2-ae0f-1879c20072e2_png_2000x3000.jpg",
		"title" : "I Am Legend",
		"director" : "Francis Lawrence",
		"year" : 2007,
		"genre" : "Horror",
		"IMDB_Rating" : 7.2,
		"ticket" : 200
	}
  ]
}
```

## Reference

1. https://github.com/typicode/json-server
2. https://vercel.com
3. https://shadowsmith.com/how-to-deploy-an-express-api-to-vercel

![OLLEHTO](front/public/title.png "Title Image")


## 🤷‍♀️ About
Visualizes "Customer Reservations" with "Density"
## 🚀 Demo

![demo](https://user-images.githubusercontent.com/34239241/117567855-00b2df80-b0f9-11eb-838d-d87a3260e3d4.gif)

## 🧐 Build With: React, Rails, Postgres
![BuildWith](buildwith.png "Build With")


## 🛠️ Installation Steps

1. Clone the repository

```bash
git clone git@github.com:h1royuki229/Density-Calendar.git
```

2. Set up

```bash
docker-compose build
docker-compose run --rm back bundle exec rails db:setup
```

3. Run the app


```bash
docker-compose up -d
```


* if you can't run front container, run the below command


```bash
cd front
npm install

cd ..
docker-compose up -d
```

4. Stop the app

```bash
docker-compose down
```


## 🙏 Links
https://github.com/g1eb/reactjs-calendar-heatmap

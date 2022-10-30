## Scape: simple task management system for teams

in this system you will be able to create and manage projects, tasks , milestones and more...

### Get started

1- Clone the project:
```shell
git clone https://github.com/sinarajabpour1998/scape.git
```

2- open the project directory in terminal:
```shell
cd scape
```

3- install necessary packages:
```shell
composer install
```

4- create env file:
```shell
cp .env.example .env
```

5- create project key:
```shell
php artisan key:generate
```

6- create necessary tables:
```shell
php artisan migrate
```

7- run the project:
```shell
php artisan serve
```

And you are good to go !

### For development only

1- install npm packages:
```shell
npm i
```

2- run development each time you made changes to scss or js files:
```shell
npm run dev
```

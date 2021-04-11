To run the website locally follow instructions in Robs blog https://blog.robsewell.com

`docker run -it --rm -v "$PWD":/usr/src/app -p "4000:4000" starefossen/github-pages`

website is at

http://localhost:4000

when you click on an event link it will take you to

http://0.0.0.0:4000/2021-04-17-datasaturday0005/

which doesn't work so you have to replace 0.0.0.0 with localhost

http://localhost:4000/2021-04-17-datasaturday0005/
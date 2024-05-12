a)
docker build -t zad1:v1.8 .

b)
docker run -p 3000:3000 -d --name zadanie1 zad1:v1.7

c)
docker logs zadanie1
curl -f http://localhost:3000

d)
docker history zad1:v1.8
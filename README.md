docker build -t nextjs-initial .

docker run -d --name=next-app -p 8080:3000 nextjs-initial docker 
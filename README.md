# semestre-empresarial-git-docker
DOCKER
docker pull hello-world
docker run hello-world

DOCKER/SQL Server
docker pull mcr.microsoft.com/mssql/server:2019-latest
docker run mcr.microsoft.com/mssql/server:2019-latest
docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=root" --name sql -h imagensql -d mcr.microsoft.com/mssql/server:2019-latest

GIT
echo "# semestre-empresarial-git-docker" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/JDAVIDMR97/semestre-empresarial-git-docker.git
git push -u origin main

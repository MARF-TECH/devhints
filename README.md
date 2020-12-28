#### devhints

## Tools & Programs  
Log
> https://www.baremetalsoft.com/baretail/

## Extensions 
Vs code 
> https://microsoft.github.io/AzureTipsAndTricks/blog/tip248.html

Visual Studio 
-- Supercharger
-- Productivity Power Tools
-- CodeMaid
-- VSColorOutput
-- Comment Remover
-- Conveyor
-- SwitchStartup
-- SlowCheetah
-- Viasfora
-- File Icons
-- VSColorOutput
-- Open Command Line
-- GoToDnSpy

## Git cmd
> https://git-scm.com/book/en/v2/Git-Tools-Rewriting-History

-- pretty log 
git config --global alias.prettylog "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"

-- create branch locally & upstream 
git branch -u origin/topic
git branch --set-upstream-to=origin/

-- create branch from tag 
git checkout tags/<tag_name> -b <branch_name>

-- delete commit before push 
git reset HEAD~1 --soft [Hard]  

-- stash 
git stash list 
git stash store -m ""
git stash pop 

-- delete branch locally & upstream 
git branch -d localBranchName
git push origin --delete remoteBranchName

-- changing history 
(change last message)
git commit --amend      --> edit message & save 
git push --force        --> u have to force the push otherwise it won't work  

(change last commit(s))
git rebase -i HEAD~3

## Interview Questions & Algorithm
csharp 
> https://www.csharpstar.com/

## Youtube 
dotnet 
> https://www.youtube.com/channel/UCNwFQFVL0RSHLsM7rAOf_hg

## Cheat Sheet 
*_ 
> https://devhints.io/

docker
> https://devhints.io/docker

elastic
> https://elasticsearch-cheatsheet.jolicode.com/

## Articles 
ddd 
> https://medium.com/@abstarreveld/implementing-dddomain-models-ports-adapters-and-cqrs-with-c-2b81403f09f7

dotnet + redis cache 
> https://medium.com/@KevinHoffman/caching-distributed-work-output-in-redis-with-asp-net-core-7d77695e6757

front + mobx 
> https://mobx-state-tree.js.org/intro/philosophy

databases 
> EF -- https://www.learnentityframeworkcore.com/
> EF -- Generic Repository + UOW PATTERN : https://stackoverflow.com/questions/52439226/net-core-unit-of-work-generic-repository-pattern/52440285

dotnet
> backgroud-services: https://blog.computedcloud.com/background-services-in-net-core-console-app/
> asp-net: http://bekenty.com/send-e-mail-in-asp-net-core-with-sendgrid/

design pattern 
> https://blog.cdemi.io/design-patterns-introduction/

## worker jobs 
azure
> https://dotnetcoretutorials.com/2018/10/09/azure-webjobs-in-net-core-part-1/

## SQL Simple db 
sql server 
> https://www.dofactory.com/sql/sample-database

## Simple Code 
SQL 
> https://github.com/Cheranga/LearnDbUp

ddd 
> https://github.com/appie2go/steal-this-code <br/>
> https://github.com/aneshas/tactical-ddd    
> https://github.com/zsajjad/rtk-demo
   
Cqrs
> https://github.com/vkhorikov/CqrsInPractice <br/>
> https://github.com/kgrzybek/sample-dotnet-core-cqrs-api        
   
GraphQL
> https://github.com/nigel-sampson/talks/tree/master/dotnet-conf-2019

dotnet + microservices
> https://github.com/MichaCo/AspNetCore.Services

Http Client 
> https://github.com/canton7/RestEase

## Starter Kit 
angular
> https://github.com/samteb/angular-7-webpack-4-boilerplate

eshop-angular 
> https://github.com/ikismail/Angular-ShoppingCart

### Editors 

## vs code 
icon themes
> https://github.com/helgardferreira/vscode-helium-icon-theme

color theme
> https://github.com/framer/syntax

## Docker 
> https://hub.docker.com/r/nshou/elasticsearch-kibana/


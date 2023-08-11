# Configuration Alias Permanently on Windows

### Follow below steps:

1. Open Git Bash with Run As Administrator,
2. Type command `nano /etc/profile.d/aliases.sh`,
3. Add alias on the file,
4. After that, `CTRL + O` to save then `CTRL + X` to exit file
5. Lastly, load file with command `source /etc/profile.d/aliases.sh`
6. Check alias bash with command `alias` then Enter

### My Alias: 
```
alias ls='ls -F --color=auto --show-control-chars'
alias ll='ls -l'
alias c='clear'
alias aliases='nano /etc/profile.d/aliases.sh'
alias status='git status'
alias push='git push origin main --force'
alias add='git add .'
alias commit='git commit -m'
alias clone='git clone'
alias clone:lrvs='git clone https://github.com/fhmiibrhimdev/laravel-react-vite-stisla.git'
alias tag='git tag'
alias push-tags='git push --tags'
alias nianrd='npm install && npm run dev'
alias nrd='npm run dev'
alias npmi='npm install'
alias nrb='npm run build'
alias controller='php artisan make:controller'
alias model='php artisan make:model'
alias seeder='php artisan make:seeder'
alias resource='php artisan make:resource'
alias serv='php artisan serve'
alias mf='php artisan migrate:fresh'
alias mfs='php artisan migrate:fresh --seed'
alias seed='php artisan db:seed'
alias routes='php artisan route:list'
alias composeri='composer install'
alias composera='composer require'
alias autoload='composer dump-autoload'
alias cache:clear='php artisan cache:clear'
alias optimize='php artisan optimize'
alias key='php artisan key:generate'
alias jwt='php artisan jwt:secret'
alias storage='php artisan storage:link'
alias cpenv='cp .env.example .env'
alias beserv='cd backend/ && php artisan serve'
alias be='cd backend/ && clear'
alias fe='cd frontend/ && clear'
alias fenrd='cd frontend/ && npm run dev'
alias sources='source /etc/profile.d/aliases.sh'

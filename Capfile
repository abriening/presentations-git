load 'deploy'
set :application, "presentations-git"
set :deploy_to, "/var/www/#{application}"
set :repository, Dir.pwd
set :deploy_via, :copy
set :copy_exclude, (Dir['*'] - Dir['images','css','js','lib','plugin','*.html']) + ['.git', '.rvmrc']
set :normalize_asset_timestamps, false
role :web, "briening.com"

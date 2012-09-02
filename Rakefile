task :deploy do
  sh %{rsync -rtzh --progress --delete --exclude="#{File.path(__FILE__)}" --exclude=.* "#{Dir.pwd}/" tatey@tatey.com:~/var/www/nextstop.me/}
end

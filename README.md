* vagrant up
* ssh-copy-id vagrant@localhost -p 2222 # passwd: vagrant
* BRANCH=master bundle exec cap stage deploy
* ssh vargrant@localhost -p 2222 "ps -ef | grep cron-job"
* tail -f log/* # check ./log/cron.log

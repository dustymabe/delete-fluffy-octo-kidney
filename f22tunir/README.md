
Edit `playbook.yml` and update `image` to point to the url of the
image you want to test.

Edit `Vagrantfile` to use the name of the F22 box on your machine. 

Execute `vagrant up` to bring up machine and run tests.

If machine is already up and you want to re-execute tests against a
different image then update `image` and then run `vagrant provision`
to re-run ansible playbook.

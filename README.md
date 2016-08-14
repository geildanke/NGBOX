# NGBOX
A vagrant base box for Angular 2 and TypeScript.

## Install

1. Clone this repository:
`git clone https://github.com/geildanke/NGBOX.git`

2. Start the vagrant box
`vagrant up`

3. SSH into the vagrant box
`vagrant ssh`

4. Create a new project within the vagrant box
```
cd /home/vagrant/ngbox_project
ng new your_new_project_name
```

5. Start coding
Changes made in the folder `ngbox_project` on the host or within the vagrant box
are synced

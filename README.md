# Kubectl Kubecon Plugin / aka CowCtl 

This plugin allows you to keep track how much time remains to the next KubeCon. It gives you a friendly reminder about the conference date and the C4P deadline. 

In order to work you need to export the following variables:
- *KUBECON* : Set the date for the next KubeCon.  You can do this by running `export KUBECON=2020/03/30`
- *KUBECONC4P* : Set the date for the C4P deadline. You can do this by running `export KUBECONC4P=2019/12/04`

![KubeCon Plugin](kubectl-kcon.gif)

# Depends on 
- Core Utils: `brew install coreutils` for gdate
- Cowsay: `brew install cowsay`

# Roadmap
- Read Conference List from GitHub
- Enable Character selection with Env Variable
- Change color on deadlines approaching
- Support windows (??)

# Kudos

Kudos to [@esteban-aliverti](http://github.com/esteban-aliverti) for the Bash/Shell knowledge, Linux `date` check contributions and CowSay reference. 


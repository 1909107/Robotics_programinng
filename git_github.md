# Basic git bash command lines.
##### The following commands will allow us to use the "GIT BASH" platform on our computer or laptop.
### -SETUP
##### This command allows us to configuring user information used across all local repositories.
### - Git config -global username (firstname lastname).
##### This command allows us to set a name that is identifiable for credit when review version history.
##### Example:  1  git config -global username 1909107
### -Git config -global user.email (valid-email).
##### This command allows us to set an email address that will be associated with each history marker.
##### Example: git config -global user.email 1909107@upy.edu.mx
### -SETUP&INIT
##### This command allows us to configuring user information, initializing and cloning repositories.
### -Git init
##### This command allows us to initialize an existing directory as a Git repository.
##### Example: $ git initInitialized empty Git repository in C:/Users/aldra/Desktop/.git/
### -Git clone (url)
##### This command allows us to retrieve an entire repository from a hosted location via URL.
##### Example:  git clone 

    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --progress            force progress reporting
    -n, --no-checkout     don't create a checkout
    --bare                create a bare repository
    --mirror              create a mirror repository (implies bare)
    -l, --local           to clone from a local repository
    --no-hardlinks        don't use local hardlinks, always copy
    -s, --shared          setup as shared repository
    --recurse-submodules[=<pathspec>]
                          initialize submodules in the clone
    --recursive ...       alias of --recurse-submodules
    -j, --jobs <n>        number of submodules cloned in parallel
    --template <template-directory>
                          directory from which templates will be used
    --reference <repo>    reference repository
    --reference-if-able <repo>
                          reference repository
    --dissociate          use --reference only while cloning
    -o, --origin <name>   use <name> instead of 'origin' to track upstream
    -b, --branch <branch>
                          checkout <branch> instead of the remote's HEAD
    -u, --upload-pack <path>
                          path to git-upload-pack on the remote
    --depth <depth>       create a shallow clone of that depth
    --shallow-since <time>
                          create a shallow clone since a specific time
    --shallow-exclude <revision>
                          deepen history of shallow clone, excluding rev
    --single-branch       clone only one branch, HEAD or --branch
    --no-tags             don't clone any tags, and make later fetches not to follow them
    --shallow-submodules  any cloned submodules will be shallow
    --separate-git-dir <gitdir>
                          separate git dir from working tree
    -c, --config <key=value>
                          set config inside the new repository
    --server-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only
    --filter <args>       object filtering
    --remote-submodules   any cloned submodules will use their remote-tracking branch
    --sparse              initialize sparse-checkout file to include only files at root.
### -Stage and commit
This command allows us to shows the status of the modified files in the directory.
### -Git status
##### This command allows us to shows the status of the modified files in the directory.
##### Example:  git status 
        LeagueClient - Shortcut.lnk
        MSI companion.lnk
        Microsoft Teams.lnk
        desktop.ini
        test/
### -Git add FILENAME.(format of the file)
##### This command allows us to adds a file to git so in the next commit it will be reflected.
##### Example: git add  ADA4_physics.txt
### -Git reset FILENAME.(format of the file)
##### This command allows us to delete or undo the file while keeping the changes in the working directory.
##### Example: git reset ADA4_physics.txt
### -Git commit -m “NAME OF THE CHANGE”
##### This command allows us the takes the staged snapshot and commits it to the project history.
##### Example: git commit -m ADA4_physics.txt
### -STAGE&SNAPSHOT
##### This command allows us to working with snapshots and the Git staging area.
### -Git branch
##### This command allows us to list your branches. (a  will appear next to the currently active branch).
##### Example: git branch.
### -Git branch (branch-name).
##### This command allows us to create a new branch at the current commit.
##### Example: git branch Angel Saenz.
### -Git checkout
##### This command allows us to switch to another branch and check it out into your working directory.
##### Example: git check out (name of the file)
### -Git -M main
##### This command allows us to return to our main branch.
##### Example: git -m main 

### -Git log
##### This command allows us to show all commits in the current branch’s history.
##### Example:  git log 
```console
$ git log
commit ca82a6dff817ec66f44342007202690a93763949
Author: Scott Chacon <schacon@gee-mail.com>
Date:   Mon Mar 17 21:52:11 2008 -0700

    Change version number

commit 085bb3bcb608e1e8451d4b2432f8ecbe6306e7e7
Author: Scott Chacon <schacon@gee-mail.com>
Date:   Sat Mar 15 16:40:33 2008 -0700

    Remove unnecessary test

commit a11bef06a3f659402fe7563abf99ad00de2209e6
Author: Scott Chacon <schacon@gee-mail.com>
Date:   Sat Mar 15 10:31:28 2008 -0700

    Initial commit
```
### -Git remote add origin 
##### This command allows us to upload our file to the github platform.
##### Example: git remote add origin https://github.com/1909107/Robotics_programinng.git
### -Git add
#####  This command allows us to command adds new or changed files in your working directory to the Git staging area
##### Example: git add (name of te file).
### -Git push -u origin main 
##### This command allows us to send it instantly to the platform.
##### Example: git push -u origin main 
### -Git pull 
##### This command allows us to we use this command to fetch and merge any commits from the tracking remote branch.
##### Example: git pull (If you have no branches you will see the following).
$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> master
### Delete a branch
### -Git branch -d test 
##### This command allows us  If we are done with the test branch and we want to delete it in the local repository, we will use the command git branch -d.
#####  Example: git branch -d test 
     

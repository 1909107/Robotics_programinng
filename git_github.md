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
##### Example: git check out --(name of the file)

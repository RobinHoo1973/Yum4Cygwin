# Yum4Cygwin
Yum for Cygwin


YUM for cygwin is a shell script helping cygwin user to install/update/search
packages of cygwin in the manners of similar to the yum functions of REDHAT.

Usage: yum [COMMAND] [OPTION] [PARAMETERS]

Commands:
  check-update        List all possible updates of installed package(s)
                      for cygwin as of now.
  clean               Clean all cache files and refresh them with latest
                      data.

  info [pkgs..]       Display the briefing information of the given package(s)
  info installed      Display the briefing information of installed package(s)
  info updates        Display the briefing information of updating package(s)

  install [pkgs..]    Install the given package(s) with required package(s)

  list [pkgs..]       List the detail information of the given package(s)
  list installed      List the detail information of the installed package(s)
  list updates        List the detail information of the updating package(s)

  remove [pkgs..]     Remove the installed package(s) given by user as well
                      as the orphan package(s) relatives.
                      

  search key-word     Search the package database for any package(s) relevant
                      the given keyword.

  update [pkgs..]     Update all packages or the package(s) given by user.

Options:
  -y, --yes    Always say yes to queries
  
  -h, --help   Show current help message of the script usages

Please Report Script Bugs to robin.hoo@hotmail.com

